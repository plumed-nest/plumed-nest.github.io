**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1909-454:63440] *** Process received signal ***
[fv-az1909-454:63440] Signal: Aborted (6)
[fv-az1909-454:63440] Signal code:  (-6)
[fv-az1909-454:63440] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05f4e45330]
[fv-az1909-454:63440] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05f4e9eb2c]
[fv-az1909-454:63440] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05f4e4527e]
[fv-az1909-454:63440] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05f4e288ff]
[fv-az1909-454:63440] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05f52a5ff5]
[fv-az1909-454:63440] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05f52bb0da]
[fv-az1909-454:63440] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05f52a5a55]
[fv-az1909-454:63440] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05f52a5a6f]
[fv-az1909-454:63440] [ 8] plumed_master(+0x146dd)[0x558e39c1a6dd]
[fv-az1909-454:63440] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05f4e2a1ca]
[fv-az1909-454:63440] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05f4e2a28b]
[fv-az1909-454:63440] [11] plumed_master(+0x15365)[0x558e39c1b365]
[fv-az1909-454:63440] *** End of error message ***
</pre>
{% endraw %}
