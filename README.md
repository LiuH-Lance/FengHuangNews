##kanfang_demo

�·������app---��ʮ��ѧϰAndroid·��
����Ҫ�������ǰ��˵������wifi����,���Ҳ���ط������app�Աȡ�

---
�������ߣ�
RealMoMo
> �����ң���ӭ��ע  
   ΢�ţ�[Real_Mo]()  
   ���䣺czb166@qq.com
-------------
####����Ŀ��: 
<br>1.����</br>
<br>2.��Ϥץ��</br>

###Ԥ������

<br>����̬�Ͳ����ˣ�����Ҫ����ֱ������MyApk��װ���С�</br>


<br>���Ž���</br>
	<br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic1.png)</br>

<br> ֱ������</br>
 <br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic2.png)</br>

<br> ��������</br>
  <br> ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic3.png)</br>

<br> ��Ƶ����</br>
  <br>  ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic4.png)</br>

<br>  ���ֽ���</br>
   <br>  ![image](https://github.com/RealMoMo/FengHuangNews/blob/master/pic/pic5.png)</br>

     
   

###��������
Android Studio2.0


### ���ذ�װ
������Ŀ�����������ʺ��㿪������build.gradle�ļ�
��������appģ�飬���������ʺ��㿪������build.gradle�ļ�
ע�⣺java-->momo���²�����Ҫ���룬�����ǵ�������¼�������İ���

```java  
  
apply plugin: 'com.android.application'

android {
    compileSdkVersion 23
    buildToolsVersion "23.0.3"

    defaultConfig {
        applicationId "momo.com.week10_project"
        minSdkVersion 16
        targetSdkVersion 23
        versionCode 1
        versionName "1.0"
    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    testCompile 'junit:junit:4.12'
    compile 'com.android.support:appcompat-v7:23.4.0'
    compile 'com.squareup.retrofit2:retrofit:2.1.0'
    compile 'com.squareup.retrofit2:converter-gson:2.1.0'
    compile 'com.squareup.retrofit2:converter-scalars:2.1.0'
    compile 'com.android.support:design:23.4.0'
    compile 'in.srain.cube:ultra-ptr:1.0.11'
    compile 'com.youth.banner:banner:1.4.4'
    compile 'com.github.bumptech.glide:glide:3.7.0'
    compile files('libs/MobCommons-2016.1107.1809.jar')
    compile files('libs/MobTools-2016.1107.1809.jar')
    compile files('libs/ShareSDK-Core-2.7.10.jar')
    compile files('libs/ShareSDK-QQ-2.7.10.jar')
    compile files('libs/ShareSDK-QZone-2.7.10.jar')
    compile files('libs/ShareSDK-SinaWeibo-2.7.10.jar')
    compile files('libs/ShareSDK-TencentWeibo-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Core-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Favorite-2.7.10.jar')
    compile files('libs/ShareSDK-Wechat-Moments-2.7.10.jar')
}

  
```

###Thanks
Everyone who has contributed code and reported issues and pull requests!



###TODO
 * 1.��appû�������湦�ܡ�
 * 2.����listview���item��û��д����չʾ���ݣ�������webviewչʾ�ġ�
 * 3.ֱ�����ݵ���Ƶ�ӿڣ�û��ץ��������������ṩ�¡�
 * 4.���Ž���ֻд������ģ��--ͷ��������������ģ��˼·����һ�¡������Ϳ����� ^_^��
 * 5.��Ƶû��ʵ�ֵ����ȥ���ŵĹ��ܡ�����listview������Ƶ�����Ƶ����ȥ���Ŷ���С�¡�
 * 6.����ģ���û��ʵ��listview item������ܣ��ӿڷ��ص����ݣ���������WebViewչʾ����Ҫ�Լ��������ݣ�д���ֽ���չʾ��
 * 7.�ҵ�ģ��ֻд��mob�������ĵ�¼��
 * 8.��ģ���listview����û��дʲô˫��ͷ���ص������Ĺ��ܡ�������д
 * 9.����ģ�����item Ĭ�����RealMo��item,ʵ�ֹ��ܵ����Ӷ��ѡ�
 * 10.webview���ض���ķ�������û����д������ת�Լ��ֻ���������Լ���д�÷������ɡ�
 * 11.��appû��ô���������Ż����⡣
 * 12.widget���µ�iconview nameview��4���Զ��壬����Ӧ����һ��������ֱ��Ū�þ��С�   ����������������������
 * 13.��Ƶ���Ž��治̫�Ѻá�
 * 14.��ֱ����android studio��װapk,weibo���ܵ�����ʵ�ֲ��˵�¼��Ҫ�Լ���assets�ļ��е�ShareSDK������

###Version
<br>1.0ʵ�ִ��¹���----2016.12.16</br>
<br>1.1����ע�͡��������----2016.12.17</br>