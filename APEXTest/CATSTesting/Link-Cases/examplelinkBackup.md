# Example Link White List

This is the white list of example links that are currently used in Docs content. This list is consumed by the content automation test system (CATS). Links from this list will be excluded from the broken link test result.

Content owners should update this list, by adding a new link if it is used as an example, or removing an existing link if it is not used anymore.

There are 4 ways to exclude example link:
* ExampleLink Keywords List: 
  * Skip the URL which host contains any item on ExampleLink Keywords list. 
  * e.g., Skip http://127.0.0.1:80 as the host contain "127.0.0.1" which on the ExampleLink Keywords List
* Example Link List: 
  * Skip the URL which equal to any item on URL list
* Host List: 
  * Skip the URL which url host equal to any item on Host list
* URL Keywords List: 
  * Skip the Url which contains any item on URL Keywords List
 
## ExampleLink Keywords List

1. 127.0.0.1
2. aadg.windows.net
3. abc.azurehdinsight.net
4. abc123.azurehdinsight.net
5. accountname
6. adatum.com
7. adfs.local
8. adfsserversame
9. adfsservicefqdn
10. adhybridhealth
11. adventure-works
12. adventure-works.com.onlinesales
13. amstest1
14. amstest1.streaming.mediaservices
15. ams-usgc-1-hos-rest-1-1
16. ams-usge-0-acs-global-1-1
17. ams-usge-1-hos-rest-1-1
18. api.aadrm
19. api.adventure-works.com
20. api.applicationinsights.io
21. api.azuredatacatalog.com
22. api.cognitive.microsoft
23. api.development.push
24. api.powerbi
25. api.sysdev.microsoft
26. api.twitter
27. app.trakstar.com
28. app_name
29. appdiscovery.azure.com
30. appname.cloudapp.net
31. app-server
32. autologon.microsoftazuread-sso
33. awebsrvr
34. azurecustomerinsights.com
35. azureilb01
36. b2cgraphapi
37. baseimagevm
38. bitsdc
39. calebb.net
40. clustername
41. clxtestax404ret
42. company
43. company.sugarondemand
44. computer01
45. computer1.domein.lokaal
46. computername
47. connector.msappproxy
51. corpproxy
52. cs.dds.microsoft
53. customer.portal.azure-api
54. customer1
55. customer2
56. datalake.azure.net
57. dc.services
58. destinationserver
59. devicesigningservice
60. devplatem
61. directaccess-webprobehost
62. directorysearcher
63. discover.aadrm.com
64. dl.windowsazure
65. domain.com
66. domain.local
67. domain.promapp
68. domemaildist
69. domena.com
70. emieportal
71. emieposturl
72. endpoint
73. example.com
74. example.facebook
75. example.org
76. expenseapp
77. expenses
78. fabrikam
79. finance
80. fqdn:5362
81. fs.anandmsft
82. global.replicon
83. graph.windows.net
84. hdiconfigactions
85. headnodefqdn
86. headnodehost
87. host-ip
88. hostname
89. hr2day.force
90. iismedia7
91. intranetupd01
92. juliakofuncapp
93. kafka-basename
94. lamp-vm.cloudapp
95. localhost
96. login.microsoftonline.com
97. machinea
98. machineb
99. machinename
100. mainserver
101. managedbackupstorage
102. management.azure
103. management.azureml.net
104. management.core
105. management.local.azurestack
106. management.usgovcloudapi
107. mdt01
108. media.windows.net
109. mediadl
110. mimcmserveraddress
111. ms-sso-test.onit
112. music.xboxlive
113. my.api
114. my.custom
115. myaccount
116. myapp
117. mybusiness
118. mycatalog.api
119. mycdn
120. myclientapp
121. mycluster
122. mycluster.azurehdinsight
123. mycompany
124. MyCompanyNameret
125. mycompanynameret.axcloud.dynamics
126. mycustomrootcomain
127. mydbaccount
128. mydemodocdbwebapp
129. mydevbox
130. mydirectorysearcherapp
131. mydomainlabel
132. myhbase
133. myhbasecluster
134. myhdinsightapp
135. myhost
136. mykv
137. mymgmtsrv
138. myorg
139. myorigin
140. myreportserver
141. mysamplealert
142. mysampleapp
143. mysecretapp1
144. myserver
145. mysharepoint
146. mysite
147. myspsite
148. mystorage
149. mystorageaccount
150. mystore1.blob
151. mytestapp
152. mytestsite
153. mytokentest
154. myvault.vault
155. mywebsite
156. myworkday
157. nerddiner
158. oldrmsserverurl
159. operator
160. otheraccount
161. packagestore
162. panel.cytanium.com
163. parliament.preview.learningpool
164. paycheck
165. payroll.myorg.com
166. phone360
167. policykeyservice
168. proweb1
169. proweb85
170. proxyserver
171. publicwebsite.com
172. pubsvr01:2718
173. quickstartcluster.westus
174. recaptcha.net
175. redirect_uri
176. retailstorescaleunit
177. rms.na.aadrm.com
178. rt.services
179. salesforce-jobscience
180. schemas.asp.net
181. schemas.datacontract.org
182. schemas.example.org
183. schemas.microsoft.com
184. schemas.system
185. schemas.xmlsoap.org
186. secure.aadcdn.microsoftonline-p.com
187. server.1234
188. servername
189. serverurl.com
190. service.sap
191. servicename
192. sharepoint-iddemo.msappproxy
193. SharePointServerName
194. some.publicdnsname
195. somedatasource
196. someone:secret
197. someremoteserver
198. someserver
199. someservice
200. somestore
201. speech.platform.bing
202. ssl.gstatic
203. sso.domain
204. sso.novatuscontracts
205. sso.tangoe
206. stageweb1
207. stageweb85
208. storageaccount
209. storageaccount.file.core.windows.net
210. storagesample.blob.core.windows.net
211. storagetestaccount001
212. storm-basename
213. sts.windows.net
214. subdomain
215. syndicatepartner
216. tableau_server
217. telemetryvalidationstore.table.core
218. tempuri1.org
219. tempuri2.org
220. test.cloudapp
221. test.stats.update
222. test001.origin.mediaservices
223. test123
224. testax3ret
225. testazmeexport
226. testdevice
227. testendpoint
228. testserver
229. teststorageaccnt
230. testweb1
231. ti.securitycenter.windows
232. todolistangular
233. todolistsangular.azurewebsites.net
234. tomcatdemo.cloudapp.net
235. tomcatexample.cloudapp.ne
236. topo00dfa4stbobaos
237. treyadfs.trey.net
238. uebi.cloudapp.net
239. uncsite
240. UserName
241. user-roster-api.sandboxcernercentral
242. usncax1aos
243. ussouthcentral.services.azureml
244. vanarsdelltd
245. vault01.vault.local.azurestack.external
246. vault010.vault.local.azurestack.global
247. vault10.vault.local.azurestack.external
248. wamsbayclus001rest-hs
249. waptenantportal
250. wasserver
251. watestsdp2008r2
252. wd3-impl-services1.workday
253. webserver01
254. website1
255. wifi.windowsphone.com
256. wingtiptoysregistry.azurecr.io
257. wsusserver
258. xleavep1941203872trial
259. xxx.dynamics.com
260. you_backend.azurewebsites
261. youarestorageaccountname
262. your_storage_account_name
263. YourAOSTenan
264. youraostenant
265. yourapp
266. yourdomain
267. yoursite
268. yourstorageaccount
269. yourtenant
270. youruniquedns
271. yourvaultname
272. yourwebapp
273. shell.azure.com
274. sp_site
275. yourcustomdomain.sharepoint.com
276. 13.72.77.9
277. 169.254.169.254
278. 172.31.194.61
279. 192.168.0.1
280. 40.121.222.19
281. 52.168.55.24
282. 52.170.203.149
283. publicIpAddress
284. publiciporfqdn
285. amstest
286. lin0823ryf2he.cloudapp.azure.com
287. myjavaapp
288. 123456
289. abcdef
290. storagesample
291. willzhan
292. adfv2storage
293. amshelloworld
294. clusterfqdn
295. keyvaultname
296. masterdns343khhde
297. masterdns343khhde
298. mykeyvault
299. myschema
300. mysfcluster
301. my-tenant
302. publiciporfqdn
303. test0
304. testblobstorage
305. user-roster-api
306. vault010
307. your-service-name
308. someone:
309. pod01-rec2.geo-name
310. smarthotel360public

## Example Link List

[https://azure.microsoft.com/regions/](https://azure.microsoft.com/regions/)

[http://www.adatum.com/MyService](http://www.adatum.com/MyService)

[https://www.microsoft.com/MyApplication](https://www.microsoft.com/MyApplication)

[http://www.openssl.org/docs/apps/openssl.html](http://www.openssl.org/docs/apps/openssl.html)

[http://www.w3.org/TR/xhtml-basic/xhtml-basic10.dtd](http://www.w3.org/TR/xhtml-basic/xhtml-basic10.dtd)

[http://www.wapforum.org/dtd/wml20.dtd](http://www.wapforum.org/dtd/wml20.dtd)

[http://www.wapforum.org/DTD/xhtml-mobile10.dtd](http://www.wapforum.org/DTD/xhtml-mobile10.dtd)

[http://www.xrml.org](http://www.xrml.org/)

[https://aadappgallery.azurewebsites.net/M](https://aadappgallery.azurewebsites.net/M)

[https://dl-ssl.google.com/android/repository/*](https://dl-ssl.google.com/android/repository/*)

[https://WSUSServer:8531](https://wsusserver:8531/)

[http://AzureILB01:81/sites/DynamicsAx](http://azureilb01:81/sites/DynamicsAx)

[https://sandbox.ax.dynamics.com/Services/AxUserManagement/Service.svc/ws2007FedHttp](https://sandbox.ax.dynamics.com/Services/AxUserManagement/Service.svc/ws2007FedHttp)

[http://*UserName*:*Password*@iismedia7/BBB.isml](http://*UserName*:*Password*@iismedia7/BBB.isml)

[http://172.31.194.61:8000/](http://172.31.194.61:8000/)

[http://192.168.50.50:19080/Explorer](http://192.168.50.50:19080/Explorer)

[http://447564652c20426f6220526f636b7321.cloudapp.net/MyHelloWorld](http://447564652c20426f6220526f636b7321.cloudapp.net/MyHelloWorld)

[http://cm12cas:8530/](http://cm12cas:8530/)

[http://d1594d4527614a09b934d470.cloudapp.net/](http://d1594d4527614a09b934d470.cloudapp.net/)

[http://marketing.azureedge.net/brochures](http://marketing.azureedge.net/brochures)

[http://marketing.azureedge.net/brochures/](http://marketing.azureedge.net/brochures/)

[http://microsoft.com/default.apsx](http://microsoft.com/default.apsx)

[https://www.microsoft.com/ApplicationName](https://www.microsoft.com/ApplicationName)

[https://api.linkedin.com/](https://api.linkedin.com/)

[https://graph.microsoft.com/v1.0/me](https://graph.microsoft.com/v1.0/me)

[https://na2.replicon.com/company/saml2/sp-sso/post](https://na2.replicon.com/company/saml2/sp-sso/post)

[https://sendgrid.com/windowsazure.html](https://sendgrid.com/windowsazure.html)

[https://service.azurewebsites.net/tables/TodoItem](https://service.azurewebsites.net/tables/TodoItem)

[https://service.azurewebsites.net/tables/TodoItem?ZUMO-API-VERSION=2.0.0](https://service.azurewebsites.net/tables/TodoItem?ZUMO-API-VERSION=2.0.0)

[https://slack.botframework.com/api/Actions](https://slack.botframework.com/api/Actions)

[https://sms.botframework.com/api/sms](https://sms.botframework.com/api/sms)

[https://waptenantportal:40005/](https://waptenantportal:40005/)

[https://www.app.com/hv/](https://www.app.com/hv/)

[https://www.app.com/hv/redirect.aspx](https://www.app.com/hv/redirect.aspx)

[https://www.healthapp.com/username/](https://www.healthapp.com/username/)

[https://www.healthapp.com/username/stats](https://www.healthapp.com/username/stats)

[https://www.tinfoilsecurity.com/saml/consume](https://www.tinfoilsecurity.com/saml/consume)

[https://aka.ms/devicelogin](https://aka.ms/devicelogin)

[https://sdfpilot.outlook.com](https://sdfpilot.outlook.com)

[https://www.pnp.com](https://www.pnp.com)

[https://www.northwindtraders.com/home/index](https://www.northwindtraders.com/home/index)

[https://analysis.windows.net/powerbi/api](https://analysis.windows.net/powerbi/api)

[https://analytics.applicationinsights.io](https://analytics.applicationinsights.io)

[https://analytics.documents.azure.com](https://analytics.documents.azure.com)

[https://signalrtestwebapp22665120.azurewebsites.net/signin-github](https://signalrtestwebapp22665120.azurewebsites.net/signin-github)

[https://www.videoindexer.ai/api/Thumbnail/3a9e38d72e/d1f5fac5-e8ae-40d9-a04a-6b2928fb5d10?accessToken=eyJ0eXAiOiJKV1QiLCJhbGciO](https://www.videoindexer.ai/api/Thumbnail/3a9e38d72e/d1f5fac5-e8ae-40d9-a04a-6b2928fb5d10?accessToken=eyJ0eXAiOiJKV1QiLCJhbGciO)

http://containercluster.westus2.cloudapp.azure.com:19080/Explorer

http://containercluster.westus2.cloudapp.azure.com:8081

http://dl.microsoft.com/eclipse/azure/servicefabric

http://download.sysinternals.com

http://events.wingtip-dpt

http://lin4hjim3l4.westus.cloudapp.azure.com:19080/Explorer

http://mysftestcluster.southcentralus.cloudapp.azure.com:19080/Explorer

http://spatial.virtualearth.net/REST/v1/data/

http://www.microsoft.com/pki/certs

http://www.microsoft.com/pkiops/certs

http://www.microsoft.com/pkiops/crl

https://13.85.80.81:8080/

https://api.cognitive.azure.ai/face/v1.0

https://api.cognitive.azure.cn/face/v1.0

https://api.push.apple.com/3/device

https://api.timeseries.azure.com

https://atlas.microsoft.com/search/address/json?

https://atlas.microsoft.com/search/address/reverse/crossstreet/json?

https://atlas.microsoft.com/search/address/reverse/json?

https://atlas.microsoft.com/search/fuzzy/json?

https://azurewebsites.net

https://bj1prod-dacsvc.chinacloudapp.cn/dacwebservice.svc

https://cawablobgrs.blob.core.windows.net

https://database.windows.net

https://enterpriseregistration.windows.net/

https://eu.manage.hub.syncfabric.windowsazure.com/Management

https://eu.provision.hub.syncfabric.windowsazure.com/Provisioning

https://eventhubs.azure.net

https://gallery.azure.com

https://gallery.cloudapi.de

https://graph.chinacloudapi.cn

https://manage.core.cloudapi.de

https://manage.hub.syncfabric.windowsazure.com/Management

https://manage.microsoftazure.de/publishsettings/index

https://management.chinacloudapi.cn

https://management.database.chinacloudapi.cn

https://management.database.windows.net

https://microsoft.com/devicelogin

https://provision.hub.syncfabric.windowsazure.com/Provisioning

https://servicebus.azure.net

https://services.azureml-test.net

https://settings-win.data.microsoft.com

https://sh1prod-dacsvc.chinacloudapp.cn/dacwebservice.svc

https://storage.azure.com

https://testlinuxcluster.westus.cloudapp.azure.com:19080

https://v10.vortex-win.data.microsoft.com

https://vault.azure.net

https://vault.microsoftazure.de

https://vortex.data.microsoft.com/collect/v1

https://us.intacct.com/support

https://labs.azure.com/

https://api.clarizen.com/v2.0/services/

http://www.azuredatacatalog.com/

https://www.azure.cn/support/legal/subscription-agreement-en/

http://xrdp.org

https://microsoft.sharepoint.com/teams/brandcentral

https://newsroom.intel.com/wp-content/uploads/sites/11/2018/03/microcode-update-guidance.pdf

https://account.activedirectory.windowsazure.com/r#/profile

https://www.azure.cn/offers/ms-mc-arz-33p-en/

http://twilio.github.io/twilio-node

http://pubs.vmware.com/vsphere-60/index.jsp#com.vmware.wssdk.dsg.doc/sdk_sg_server_certificate_Appendixes.6.4.html

http://www.uie.com/articles/faceted_search/

https://sharepoint/

https://api.github.com/scim/v2/organizations/

https://secure.aadcdn.microsoftonline-p.de/

http://www.visualstudio.com/get-started/debug-your-app-vs.aspx


## Host List

1. 10.10.10.10
2. 2-app1
3. app
4. app1
5. app2
6. example
7. files
8. fqdn
9. host
10. iisserver
11. internal
12. ipaddress
13. jenkins2517454.eastus.cloudapp.azure.com
14. lob1
15. machine
16. mail
17. management.microsoftazure.de
18. namespace
19. nimbuscdn-nimbuspm.streaming.mediaservices.windows.net
20. myVmWeb
21. owa
22. Phone360
23. portal.local.azurestack.external
27. proxy
28. proxyfqdn
29. proxyipaddress
30. rest.media.azure.net
31. seapod01coord1exsapk732.blob.core.windows.net
32. server
33. servername
34. servicefabric
35. server-ip
36. smtserver
37. sp
38. stormcluster.azurehdinsight.net
39. url
40. webserver
41. xyz
42. wingtipb2cfuncs.azurewebsites.net
43. support.one-team.com
44. 1.2.3.4

## URL Keywords List

1. 127.0.0.1
2. adsf
3. consoto
4. constoso
5. contoso
6. developer.microsoft.com/graph/docs/api-reference/v1.0/api
7. fabrikamfibercallcenter
8. publicipaddresses
9. signalrtestwebapp
10. test123
11. your_rg
12. your_sub_id
13. your_vmss
14. your-vm-ip
15. kailani
16. myvmweb

