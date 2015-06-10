##利用 eclipse，建立 Maven web 專案

###環境
1. Mac
2. eclipse-j2ee
3. java 1.7

###參考文章

1. http://blog.csdn.net/zhshulin/article/details/37921705


###實踐過程中遇到的ＢＵＧ

1. 無法轉換為 3.0 web 專案

	解決方法：http://stackoverflow.com/questions/18122336/cannot-change-version-of-project-facet-dynamic-web-module-to-3-0/18632054#18632054

	修改 <project>/.settings/org.eclipse.wstcommmon.project.facet.core.xml


	 	<installed facet="jst.web" version="3.0"/>



