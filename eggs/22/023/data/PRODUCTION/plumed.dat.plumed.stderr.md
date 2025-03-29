**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1909-454:63532] *** Process received signal ***
[fv-az1909-454:63532] Signal: Aborted (6)
[fv-az1909-454:63532] Signal code:  (-6)
[fv-az1909-454:63532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2473045330]
[fv-az1909-454:63532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f247309eb2c]
[fv-az1909-454:63532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f247304527e]
[fv-az1909-454:63532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24730288ff]
[fv-az1909-454:63532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24734a5ff5]
[fv-az1909-454:63532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24734bb0da]
[fv-az1909-454:63532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24734a5a55]
[fv-az1909-454:63532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24734a5a6f]
[fv-az1909-454:63532] [ 8] plumed(+0x146dd)[0x55af5bc056dd]
[fv-az1909-454:63532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f247302a1ca]
[fv-az1909-454:63532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f247302a28b]
[fv-az1909-454:63532] [11] plumed(+0x15365)[0x55af5bc06365]
[fv-az1909-454:63532] *** End of error message ***
</pre>
{% endraw %}
