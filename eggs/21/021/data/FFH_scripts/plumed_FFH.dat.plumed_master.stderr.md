**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1280-696:09530] *** Process received signal ***
[fv-az1280-696:09530] Signal: Aborted (6)
[fv-az1280-696:09530] Signal code:  (-6)
[fv-az1280-696:09530] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faef2645330]
[fv-az1280-696:09530] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faef269eb2c]
[fv-az1280-696:09530] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faef264527e]
[fv-az1280-696:09530] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faef26288ff]
[fv-az1280-696:09530] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faef2aa5ff5]
[fv-az1280-696:09530] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faef2abb0da]
[fv-az1280-696:09530] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faef2aa5a55]
[fv-az1280-696:09530] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faef2aa5a6f]
[fv-az1280-696:09530] [ 8] plumed_master(+0x146dd)[0x560290cef6dd]
[fv-az1280-696:09530] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faef262a1ca]
[fv-az1280-696:09530] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faef262a28b]
[fv-az1280-696:09530] [11] plumed_master(+0x15365)[0x560290cf0365]
[fv-az1280-696:09530] *** End of error message ***
</pre>
{% endraw %}
