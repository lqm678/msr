* 2017-05-06 14:21:27 CST Genereated by ```generate-summary-table.bat perf\full-Cygwin-comparison.log``` 
* CYGWIN_NT-10.0 2.6.0(0.304/5/3) x86_64 Cygwin + 32 GB RAM + 4 Cores Intel(R) Xeon(R) CPU E5-1630 v3 @ 3.70GHz 

| EXE | Cost | To find | Type | Text case | File rows | File size | System Info |
| -- | -- | -- | -- | -- | -- | -- | -- |
| findstr | **2**.*836* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **3**.*335* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **2**.*263* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **4**.*966* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*649* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **3**.*666* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **65**.*611* s | ```'Error.*found'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*771* s | ```'Error.*found'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **4**.*480* s | ```'Error.*found'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **90**.*423* s | ```'Error.*found'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*508* s | ```'Error.*found'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **9**.*091* s | ```'Error.*found'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **2**.*896* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **3**.*479* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **2**.*261* s | ```Exception``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **4**.*955* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*728* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **3**.*774* s | ```Exception``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **5**.*621* s | ```'[0-9]*Exception[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **3**.*532* s | ```'[0-9]*Exception[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **10**.*096* s | ```'[0-9]*Exception[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **27**.*736* s | ```'[0-9]*Exception[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*765* s | ```'[0-9]*Exception[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **18**.*260* s | ```'[0-9]*Exception[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **2**.*007* s | ```ExceptionX``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **2**.*320* s | ```ExceptionX``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **1**.*470* s | ```ExceptionX``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **6**.*130* s | ```ExceptionX``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*553* s | ```ExceptionX``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **3**.*112* s | ```ExceptionX``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **5**.*246* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **2**.*356* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **9**.*729* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **28**.*175* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*403* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **18**.*145* s | ```'[0-9]*ExceptionX[0-9]*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **1**.*995* s | ```Not-Exist``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **3**.*024* s | ```Not-Exist``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **1**.*439* s | ```Not-Exist``` | Plain | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **1**.*982* s | ```Not-Exist``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*786* s | ```Not-Exist``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **2**.*981* s | ```Not-Exist``` | Plain | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **2**.*461* s | ```'Not-exist.*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **2**.*844* s | ```'Not-exist.*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **3**.*317* s | ```'Not-exist.*'``` | Regex | sensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| findstr | **10**.*904* s | ```'Not-exist.*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| grep | **6**.*614* s | ```'Not-exist.*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |
| msr | **4**.*999* s | ```'Not-exist.*'``` | Regex | insensitive | 3332543 | 1.39 GB | CYGWIN_NT |