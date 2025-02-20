**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az1720-841:11555] *** Process received signal ***
[fv-az1720-841:11555] Signal: Aborted (6)
[fv-az1720-841:11555] Signal code:  (-6)
[fv-az1720-841:11555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feface45330]
[fv-az1720-841:11555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feface9eb2c]
[fv-az1720-841:11555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feface4527e]
[fv-az1720-841:11555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feface288ff]
[fv-az1720-841:11555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fefad2a5ff5]
[fv-az1720-841:11555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fefad2bb0da]
[fv-az1720-841:11555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fefad2a5a55]
[fv-az1720-841:11555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fefad2a5a6f]
[fv-az1720-841:11555] [ 8] plumed_master(+0x146dd)[0x55d73a3776dd]
[fv-az1720-841:11555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feface2a1ca]
[fv-az1720-841:11555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feface2a28b]
[fv-az1720-841:11555] [11] plumed_master(+0x15365)[0x55d73a378365]
[fv-az1720-841:11555] *** End of error message ***
</pre>
{% endraw %}
