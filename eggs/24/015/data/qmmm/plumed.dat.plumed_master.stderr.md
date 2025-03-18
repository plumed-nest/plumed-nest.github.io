**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1377-740:60944] *** Process received signal ***
[fv-az1377-740:60944] Signal: Aborted (6)
[fv-az1377-740:60944] Signal code:  (-6)
[fv-az1377-740:60944] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f50dd045330]
[fv-az1377-740:60944] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f50dd09eb2c]
[fv-az1377-740:60944] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f50dd04527e]
[fv-az1377-740:60944] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50dd0288ff]
[fv-az1377-740:60944] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50dd4a5ff5]
[fv-az1377-740:60944] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50dd4bb0da]
[fv-az1377-740:60944] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50dd4a5a55]
[fv-az1377-740:60944] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50dd4a5a6f]
[fv-az1377-740:60944] [ 8] plumed_master(+0x146dd)[0x55a0e25086dd]
[fv-az1377-740:60944] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f50dd02a1ca]
[fv-az1377-740:60944] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f50dd02a28b]
[fv-az1377-740:60944] [11] plumed_master(+0x15365)[0x55a0e2509365]
[fv-az1377-740:60944] *** End of error message ***
</pre>
{% endraw %}
