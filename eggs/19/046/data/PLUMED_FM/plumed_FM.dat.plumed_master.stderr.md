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
[fv-az1267-279:69258] *** Process received signal ***
[fv-az1267-279:69258] Signal: Aborted (6)
[fv-az1267-279:69258] Signal code:  (-6)
[fv-az1267-279:69258] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b8e845330]
[fv-az1267-279:69258] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b8e89eb2c]
[fv-az1267-279:69258] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b8e84527e]
[fv-az1267-279:69258] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b8e8288ff]
[fv-az1267-279:69258] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b8eca5ff5]
[fv-az1267-279:69258] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b8ecbb0da]
[fv-az1267-279:69258] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b8eca5a55]
[fv-az1267-279:69258] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b8eca5a6f]
[fv-az1267-279:69258] [ 8] plumed_master(+0x146dd)[0x5570686506dd]
[fv-az1267-279:69258] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b8e82a1ca]
[fv-az1267-279:69258] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b8e82a28b]
[fv-az1267-279:69258] [11] plumed_master(+0x15365)[0x557068651365]
[fv-az1267-279:69258] *** End of error message ***
</pre>
{% endraw %}
