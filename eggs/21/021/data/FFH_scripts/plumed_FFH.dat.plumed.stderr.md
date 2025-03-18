**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1377-740:63859] *** Process received signal ***
[fv-az1377-740:63859] Signal: Aborted (6)
[fv-az1377-740:63859] Signal code:  (-6)
[fv-az1377-740:63859] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ef0445330]
[fv-az1377-740:63859] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ef049eb2c]
[fv-az1377-740:63859] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ef044527e]
[fv-az1377-740:63859] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ef04288ff]
[fv-az1377-740:63859] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ef08a5ff5]
[fv-az1377-740:63859] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ef08bb0da]
[fv-az1377-740:63859] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ef08a5a55]
[fv-az1377-740:63859] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ef08a5a6f]
[fv-az1377-740:63859] [ 8] plumed(+0x146dd)[0x5619a99636dd]
[fv-az1377-740:63859] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ef042a1ca]
[fv-az1377-740:63859] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ef042a28b]
[fv-az1377-740:63859] [11] plumed(+0x15365)[0x5619a9964365]
[fv-az1377-740:63859] *** End of error message ***
</pre>
{% endraw %}
