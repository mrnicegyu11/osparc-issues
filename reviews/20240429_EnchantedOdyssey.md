# Review Meeting - April 29, 2024
<img width="712" alt="image" src="https://github.com/ITISFoundation/osparc-issues/assets/87664284/b721d0be-f6f6-41e7-b61b-05629ab83511">

## Sprint 🏃
- [**Enchanted Odyssey**](2024_04_29_EnchantedOdyssey.md)
- Scrum Master: [SCA]

### Dashboards 📊

- [POs' Backlog](https://github.com/orgs/ITISFoundation/projects/15/views/14) (BUDGETS)
- [Sprint Scrum Wall](https://github.com/orgs/ITISFoundation/projects/15/views/11) (developers' view)

### Agenda 📝

|Topic|Title|Presenter|Status| Start-Time| Duration |
|--|--|--|--|--|--|
|[#1309]|**TIP on AWS**|||
||<blockquote>[#631] Add tip.science dedicated deployment on aws-zmt|[JQ], [DK], [OM], [YH], [MD]|||
||<blockquote>[#5628] Clean-Up and Audit tip.itis.swiss osparc-simcore|[MD], [PC], [SAN]|||
||<blockquote>[#632] Migrate data from tip.itis.swiss osparc-ops-environments|[YH], [MD]|||
||<blockquote>[#5625] Add tip.science nicely styled maintenance page osparc-simcore|[JQ]|_Done_||1
||<blockquote>[#5627] Make tip.itis.swiss billable osparc-simcore#5627|[MEST], [MD], [PC]|||
||<blockquote>[#645] Enable tip.science v1 and v2 dynamic and comp autoscaling osparc-ops-environments#645|[YH], [DK], [SAN]|||
||<blockquote>[#5630] Setup E2E tests on TIP osparc-simcore#5630|[YH], [MD], [DK], [OM], [SAN]|||
||<blockquote>[#1396] Do not auto start TIP services #1396|[OM]|||
|[#1343]|**Meta-modeling merged in master**|||||
||<blockquote>[#1363] Map service for metamodelling #1363|[WVG]|||
||<blockquote>[#1366] Dakota service for metamodelling #1366|[WVG]|||
||<blockquote>[#1291] Merge the Studies API implementations #1291|[MB], [PC], [WVG]|||
||<blockquote>[#1360] Add a file probe #1360|[WVG]|||
||<blockquote>[#1362] Bring osparc-filecomms under itis-foundation github #1362|[WVG]|||
||<blockquote>[#1364] Deploy osparc_client with new endpoints to pypi #1364|[MB]|||
|[#1328]|**Maintenance / Dev Issues**||||
||<blockquote>[#5493] External clusters: Provide metrics of all of them clusters for prometheus osparc-simcore#5493|[SAN]|_Done_||2
||<blockquote>[#5606] Clusters-keeper: if application is not responding, then it prevents starting dynamic services osparc-simcore#5606|[SAN]|_Done_||0
|[#1337]|**OPs Issues**||||
||<blockquote> ? |[DK], [YH]|||
|[#1305]|**User Feedback**||||
||<blockquote> Send email with invoice|[MD]|||
||<blockquote>[#1380] Simplify cluster name|[MaG]|Done|| 1'
||<blockquote>[#1381] Renmove Skull|[MaG]|Done|| 1'
||<blockquote>[#1382] HTML Support for Reports|[MaG]| Done| | 1'
|[#1327]|**Performance Improvements for Large Projects**||||
||<blockquote>[#1349] Improve the service startup progress display #1349|[JQ], [OM], [SAN]|_Ongoing_||
||<blockquote>[#5614] Architecture: Make services restartable osparc-simcore#5614|[ANE], [MB], [MD], [SAN]|_Ongoing_||
||<blockquote>[#5293] Improve logging parsing of services such as isolve osparc-simcore#5293|[SAN]|||
|[#1331]|**S4L Application**|||||
||<blockquote>[#1336] Task Manager improvements #1336|[MaG], [IP]| Done | | 2'
||<blockquote>[#1311] 2D plots #1311|[SCA]|Done||1'
||<blockquote>[#1318] Screen capture #1318|[MaG], [IP]| Done | | 2'
||<blockquote>[#1320] IMSAFE|[MaG]| Done | | 5'
||<blockquote>[#1317] UI Form Layouts|[JQ]|_In Progress_||
|[#1332]|**NIH Year 7**|||||
||<blockquote>[#1080] Portal Development #1080|[IP]|||
||<blockquote>[#1112] o²S²PARC API Functionality for variability assessment #1112|[MB][WVG]|||
||<blockquote>[#1340] sim4life.lite reduced mode (CAD editing) #1340|[MaG]| Done | | 3'
||<blockquote>[#1092] Facilitation of Service Creation #1092|[EI], [PC]|||
||<blockquote>[#1102] DevOps Infrastructure and Automation (3/3) #1102|[YH], [DK]|||
||<blockquote>[#1306] Authentication service #1306||||
|[#1333]|**Platform Improvements**|||||
||<blockquote>[#1315] 2FA Improvements #1315|[MD], [OM]|||
||<blockquote>[#1307] Resource Tracking improvements #1307|[ANE], [MD]|||
|[#1335]|**Working Groups**|||||
||<blockquote>[#1342] S4L UI Unification #1342|[SCA]|Ongoing||2'
||<blockquote>[#1312] IMAnalytics on the web #1312|[CFU], [MaG], [MD] | Done || 0'
||<blockquote>[#1321] Desktop Integration Working Group #1321|[MaG], [MB], [OM]| Done | | 0'
||<blockquote>[#1324] On-Premise Deployment Working Group #1324|[PC]|||
||<blockquote>[#1322] Registration / Login Working Group #1322|[Nik]|||
||<blockquote>[#1325] Marketplace Working Group #1325|[DK]|||
||<blockquote>[#1326] Real time collaboration Working Group #1326|[OM]|||
||<blockquote>[#1329] Versioning Working Group #1329|[MaG], [OM], [SCA]|Done|| 0'
||<blockquote>[#1330] VIP Service Working Group #1330|[MaG]|Done|| 0'
||<blockquote>[#1339] Pre-Setup Cluster Working Group #1339|[MD], [MaG], [SAN]|||
||<blockquote>[#1339] Metamodeling and Control: working group #1316|[WVG]|||
||<blockquote>[#1310] Workbench and MATCH working group #1310|[SCA], [IP]|Done||2'


##### Status Legend

- _Todo_: no work done on this issue. This is the first time it apprears in a sprint.
- _Paused_: this issue was not scheduled/skipped for this sprint
- _In Progress_: this issue is still under development
- _Done_: no more work left to do on this issue. PO can review an decide to close or reopen.
- _Ongoing_: a recurrent task

### Deployed environments 🚀

- AWS cluster (us-east-1, ZMT)
  - [master_zmt](https://sim4life.io) (Testers only)
- AWS cluster (us-east-1, STRIDES)
  - [staging_aws](https://staging.osparc.io) (Testers only)
  - [production_aws](https://osparc.io)
- Z43 cluster (ch-zh)
  - [staging_z43](http://osparc-staging.speag.com) (Testers only)
  - [production_z43](http://osparc.speag.com)
  - [ti-plan.itis.swiss](http://ti-plan.itis.swiss)
  - [master](https://osparc-master.speag.com) (developers only)

- [Platform releases](https://github.com/ITISFoundation/osparc-simcore/releases)


[online]: http://status.osparc.io/
[operational]: https://git.speag.com/oSparc/e2e-testing/-/pipelines
[performant]: https://git.speag.com/oSparc/e2e-portal-testing/-/pipelines

[s4l-feedback]: https://z43.fogbugz.com/f/filters/1437/00-Sim4Life-web-Testing-w-Backlog

[#631]: https://github.com/ITISFoundation/osparc-ops-environments/issues/631
[#632]: https://github.com/ITISFoundation/osparc-ops-environments/issues/632
[#645]: https://github.com/ITISFoundation/osparc-ops-environments/issues/645

[#1080]: https://github.com/ITISFoundation/osparc-issues/issues/1080
[#1092]: https://github.com/ITISFoundation/osparc-issues/issues/1092
[#1102]: https://github.com/ITISFoundation/osparc-issues/issues/1102
[#1112]: https://github.com/ITISFoundation/osparc-issues/issues/1112
[#1291]: https://github.com/ITISFoundation/osparc-issues/issues/1291
[#1305]: https://github.com/ITISFoundation/osparc-issues/issues/1305
[#1306]: https://github.com/ITISFoundation/osparc-issues/issues/1306
[#1307]: https://github.com/ITISFoundation/osparc-issues/issues/1307
[#1309]: https://github.com/ITISFoundation/osparc-issues/issues/1309
[#1310]: https://github.com/ITISFoundation/osparc-issues/issues/1310
[#1311]: https://github.com/ITISFoundation/osparc-issues/issues/1311
[#1312]: https://github.com/ITISFoundation/osparc-issues/issues/1312
[#1315]: https://github.com/ITISFoundation/osparc-issues/issues/1315
[#1317]: https://github.com/ITISFoundation/osparc-issues/issues/1317
[#1318]: https://github.com/ITISFoundation/osparc-issues/issues/1318
[#1320]: https://github.com/ITISFoundation/osparc-issues/issues/1320
[#1321]: https://github.com/ITISFoundation/osparc-issues/issues/1321
[#1322]: https://github.com/ITISFoundation/osparc-issues/issues/1322
[#1324]: https://github.com/ITISFoundation/osparc-issues/issues/1324
[#1325]: https://github.com/ITISFoundation/osparc-issues/issues/1325
[#1326]: https://github.com/ITISFoundation/osparc-issues/issues/1326
[#1327]: https://github.com/ITISFoundation/osparc-issues/issues/1327
[#1328]: https://github.com/ITISFoundation/osparc-issues/issues/1328
[#1329]: https://github.com/ITISFoundation/osparc-issues/issues/1329
[#1330]: https://github.com/ITISFoundation/osparc-issues/issues/1330
[#1331]: https://github.com/ITISFoundation/osparc-issues/issues/1331
[#1332]: https://github.com/ITISFoundation/osparc-issues/issues/1332
[#1333]: https://github.com/ITISFoundation/osparc-issues/issues/1333
[#1335]: https://github.com/ITISFoundation/osparc-issues/issues/1335
[#1336]: https://github.com/ITISFoundation/osparc-issues/issues/1336
[#1337]: https://github.com/ITISFoundation/osparc-issues/issues/1337
[#1339]: https://github.com/ITISFoundation/osparc-issues/issues/1339
[#1340]: https://github.com/ITISFoundation/osparc-issues/issues/1340
[#1342]: https://github.com/ITISFoundation/osparc-issues/issues/1342
[#1343]: https://github.com/ITISFoundation/osparc-issues/issues/1343
[#1345]: https://github.com/ITISFoundation/osparc-issues/issues/1345
[#1349]: https://github.com/ITISFoundation/osparc-issues/issues/1349
[#1351]: https://github.com/ITISFoundation/osparc-issues/issues/1351
[#1360]: https://github.com/ITISFoundation/osparc-issues/issues/1360
[#1362]: https://github.com/ITISFoundation/osparc-issues/issues/1362
[#1363]: https://github.com/ITISFoundation/osparc-issues/issues/1363
[#1364]: https://github.com/ITISFoundation/osparc-issues/issues/1364
[#1366]: https://github.com/ITISFoundation/osparc-issues/issues/1366
[#1380]: https://github.com/ITISFoundation/osparc-issues/issues/1380
[#1381]: https://github.com/ITISFoundation/osparc-issues/issues/1381
[#1382]: https://github.com/ITISFoundation/osparc-issues/issues/1382
[#1396]: https://github.com/ITISFoundation/osparc-issues/issues/1396

[#5293]: https://github.com/ITISFoundation/osparc-simcore/issues/5293
[#5493]: https://github.com/ITISFoundation/osparc-simcore/issues/5493
[#5606]: https://github.com/ITISFoundation/osparc-simcore/issues/5606
[#5614]: https://github.com/ITISFoundation/osparc-simcore/issues/5614
[#5625]: https://github.com/ITISFoundation/osparc-simcore/issues/5625
[#5627]: https://github.com/ITISFoundation/osparc-simcore/issues/5627
[#5628]: https://github.com/ITISFoundation/osparc-simcore/issues/5628
[#5630]: https://github.com/ITISFoundation/osparc-simcore/issues/5630


[ANE]:https://github.com/GitHK
[BL]:https://github.com/dyollb
[DK]:https://github.com/mrnicegyu11
[EI]:https://github.com/elisabettai
[IP]:https://github.com/ignapas
[MB]:https://github.com/bisgaard-itis
[MD]:https://github.com/matusdrobuliak66
[MaG]:https://github.com/mguidon
[Nik]:https://github.com/drniiken
[OM]:https://github.com/odeimaiz
[PC]:https://github.com/pcrespov
[SAN]:https://github.com/sanderegg
[SB]:https://github.com/sbenkler
[SCA]:https://github.com/SCA-ZMT
[TN]:https://github.com/newton1985
[YH]:https://github.com/YuryHrytsuk
[JQ]:https://github.com/jsaq007
[MEST]:https://github.com/konohana0608
[WVG]: https://github.com/wvangeit