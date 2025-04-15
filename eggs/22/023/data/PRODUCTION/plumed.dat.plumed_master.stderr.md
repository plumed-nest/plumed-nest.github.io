**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1719-82:63551] *** Process received signal ***
[fv-az1719-82:63551] Signal: Aborted (6)
[fv-az1719-82:63551] Signal code:  (-6)
[fv-az1719-82:63551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34eea45330]
[fv-az1719-82:63551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34eea9eb2c]
[fv-az1719-82:63551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34eea4527e]
[fv-az1719-82:63551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34eea288ff]
[fv-az1719-82:63551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34eeea5ff5]
[fv-az1719-82:63551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34eeebb0da]
[fv-az1719-82:63551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34eeea5a55]
[fv-az1719-82:63551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34eeea5a6f]
[fv-az1719-82:63551] [ 8] plumed_master(+0x146dd)[0x560c3f8606dd]
[fv-az1719-82:63551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34eea2a1ca]
[fv-az1719-82:63551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34eea2a28b]
[fv-az1719-82:63551] [11] plumed_master(+0x15365)[0x560c3f861365]
[fv-az1719-82:63551] *** End of error message ***
</pre>
{% endraw %}
