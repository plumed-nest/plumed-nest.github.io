**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[runnervmeorf1:11498] *** Process received signal ***
[runnervmeorf1:11498] Signal: Aborted (6)
[runnervmeorf1:11498] Signal code:  (-6)
[runnervmeorf1:11498] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5fd2245330]
[runnervmeorf1:11498] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5fd229eb2c]
[runnervmeorf1:11498] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5fd224527e]
[runnervmeorf1:11498] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5fd22288ff]
[runnervmeorf1:11498] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5fd26a5ff5]
[runnervmeorf1:11498] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5fd26bb0da]
[runnervmeorf1:11498] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5fd26a5a55]
[runnervmeorf1:11498] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5fd26a5a6f]
[runnervmeorf1:11498] [ 8] plumed_master(+0x146dd)[0x5631d12916dd]
[runnervmeorf1:11498] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5fd222a1ca]
[runnervmeorf1:11498] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5fd222a28b]
[runnervmeorf1:11498] [11] plumed_master(+0x15365)[0x5631d1292365]
[runnervmeorf1:11498] *** End of error message ***
</pre>
{% endraw %}
