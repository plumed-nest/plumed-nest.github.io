**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:61461] *** Process received signal ***
[fv-az1701-508:61461] Signal: Aborted (6)
[fv-az1701-508:61461] Signal code:  (-6)
[fv-az1701-508:61461] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40b0e45330]
[fv-az1701-508:61461] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40b0e9eb2c]
[fv-az1701-508:61461] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40b0e4527e]
[fv-az1701-508:61461] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40b0e288ff]
[fv-az1701-508:61461] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40b12a5ff5]
[fv-az1701-508:61461] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40b12bb0da]
[fv-az1701-508:61461] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40b12a5a55]
[fv-az1701-508:61461] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40b12a5a6f]
[fv-az1701-508:61461] [ 8] plumed_master(+0x146dd)[0x5573dea7d6dd]
[fv-az1701-508:61461] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40b0e2a1ca]
[fv-az1701-508:61461] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40b0e2a28b]
[fv-az1701-508:61461] [11] plumed_master(+0x15365)[0x5573dea7e365]
[fv-az1701-508:61461] *** End of error message ***
</pre>
{% endraw %}
