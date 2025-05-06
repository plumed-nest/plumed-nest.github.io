**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1696-883:67508] *** Process received signal ***
[fv-az1696-883:67508] Signal: Aborted (6)
[fv-az1696-883:67508] Signal code:  (-6)
[fv-az1696-883:67508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb170645330]
[fv-az1696-883:67508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb17069eb2c]
[fv-az1696-883:67508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb17064527e]
[fv-az1696-883:67508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1706288ff]
[fv-az1696-883:67508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb170aa5ff5]
[fv-az1696-883:67508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb170abb0da]
[fv-az1696-883:67508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb170aa5a55]
[fv-az1696-883:67508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb170aa5a6f]
[fv-az1696-883:67508] [ 8] plumed_master(+0x146dd)[0x5587c65966dd]
[fv-az1696-883:67508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb17062a1ca]
[fv-az1696-883:67508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb17062a28b]
[fv-az1696-883:67508] [11] plumed_master(+0x15365)[0x5587c6597365]
[fv-az1696-883:67508] *** End of error message ***
</pre>
{% endraw %}
