**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1360-658:08116] *** Process received signal ***
[fv-az1360-658:08116] Signal: Aborted (6)
[fv-az1360-658:08116] Signal code:  (-6)
[fv-az1360-658:08116] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3942045330]
[fv-az1360-658:08116] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f394209eb2c]
[fv-az1360-658:08116] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f394204527e]
[fv-az1360-658:08116] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39420288ff]
[fv-az1360-658:08116] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39424a5ff5]
[fv-az1360-658:08116] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39424bb0da]
[fv-az1360-658:08116] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39424a5a55]
[fv-az1360-658:08116] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39424a5a6f]
[fv-az1360-658:08116] [ 8] plumed_master(+0x146dd)[0x55fbeb4aa6dd]
[fv-az1360-658:08116] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f394202a1ca]
[fv-az1360-658:08116] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f394202a28b]
[fv-az1360-658:08116] [11] plumed_master(+0x15365)[0x55fbeb4ab365]
[fv-az1360-658:08116] *** End of error message ***
</pre>
{% endraw %}
