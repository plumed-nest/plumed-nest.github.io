**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:05487] *** Process received signal ***
[fv-az1280-696:05487] Signal: Aborted (6)
[fv-az1280-696:05487] Signal code:  (-6)
[fv-az1280-696:05487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1b43645330]
[fv-az1280-696:05487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1b4369eb2c]
[fv-az1280-696:05487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1b4364527e]
[fv-az1280-696:05487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1b436288ff]
[fv-az1280-696:05487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1b43aa5ff5]
[fv-az1280-696:05487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1b43abb0da]
[fv-az1280-696:05487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1b43aa5a55]
[fv-az1280-696:05487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1b43aa5a6f]
[fv-az1280-696:05487] [ 8] plumed(+0x146dd)[0x5604b41646dd]
[fv-az1280-696:05487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1b4362a1ca]
[fv-az1280-696:05487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1b4362a28b]
[fv-az1280-696:05487] [11] plumed(+0x15365)[0x5604b4165365]
[fv-az1280-696:05487] *** End of error message ***
</pre>
{% endraw %}
