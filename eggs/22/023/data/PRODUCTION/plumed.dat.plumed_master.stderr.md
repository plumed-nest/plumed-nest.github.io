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
[fv-az816-356:08486] *** Process received signal ***
[fv-az816-356:08486] Signal: Aborted (6)
[fv-az816-356:08486] Signal code:  (-6)
[fv-az816-356:08486] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa36cc45330]
[fv-az816-356:08486] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa36cc9eb2c]
[fv-az816-356:08486] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa36cc4527e]
[fv-az816-356:08486] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa36cc288ff]
[fv-az816-356:08486] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa36d0a5ff5]
[fv-az816-356:08486] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa36d0bb0da]
[fv-az816-356:08486] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa36d0a5a55]
[fv-az816-356:08486] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa36d0a5a6f]
[fv-az816-356:08486] [ 8] plumed_master(+0x146dd)[0x55c447cb76dd]
[fv-az816-356:08486] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa36cc2a1ca]
[fv-az816-356:08486] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa36cc2a28b]
[fv-az816-356:08486] [11] plumed_master(+0x15365)[0x55c447cb8365]
[fv-az816-356:08486] *** End of error message ***
</pre>
{% endraw %}
