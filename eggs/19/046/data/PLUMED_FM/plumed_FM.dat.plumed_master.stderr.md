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
[fv-az802-475:14267] *** Process received signal ***
[fv-az802-475:14267] Signal: Aborted (6)
[fv-az802-475:14267] Signal code:  (-6)
[fv-az802-475:14267] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d01c45330]
[fv-az802-475:14267] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d01c9eb2c]
[fv-az802-475:14267] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d01c4527e]
[fv-az802-475:14267] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d01c288ff]
[fv-az802-475:14267] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d020a5ff5]
[fv-az802-475:14267] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d020bb0da]
[fv-az802-475:14267] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d020a5a55]
[fv-az802-475:14267] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d020a5a6f]
[fv-az802-475:14267] [ 8] plumed_master(+0x146dd)[0x55a86d9c76dd]
[fv-az802-475:14267] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d01c2a1ca]
[fv-az802-475:14267] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d01c2a28b]
[fv-az802-475:14267] [11] plumed_master(+0x15365)[0x55a86d9c8365]
[fv-az802-475:14267] *** End of error message ***
</pre>
{% endraw %}
