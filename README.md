This XML file does not appear to have any style information associated with it. The document tree is shown below.
<!--
 Configuration Start: Please customize following configuration 
-->
<widget xmlns="http://www.w3.org/ns/widgets" xmlns:gap="http://phonegap.com/ns/1.0" id="phonegap-web-template.pulipuli.info" version="1.0.0">
<name>軟體名稱</name>
<description>軟體描述</description>
<author href="作者網站" email="作者email">作者姓名</author>
 <!--  Configuration End  -->
 <!--   allows access to any external resource.  -->
<access origin="*"/>
<allow-navigation href="*"/>
<content src="index.html"/>
<icon src="icon.png"/>
 <!--  https://build.phonegap.com/current-support  -->
<preference name="phonegap-version" value="cli-6.5.0"/>
 <!--  防止太多權限  -->
<preference name="permissions" value="none"/>
 <!--  只保留最低的權限  -->
<feature name="http://api.phonegap.com/1.0/network"/>
 <!--  外掛  -->
<plugin name="cordova-plugin-inappbrowser" spec="~1.7.1"/>
<plugin name="cordova-plugin-network-information" spec="~1.3.3"/>
<plugin name="cordova-plugin-whitelist" spec="~1.3.2"/>
</widget>
