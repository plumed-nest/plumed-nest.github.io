**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[fv-az1444-322:06690] *** Process received signal ***
[fv-az1444-322:06690] Signal: Aborted (6)
[fv-az1444-322:06690] Signal code:  (-6)
[fv-az1444-322:06690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7b5e45330]
[fv-az1444-322:06690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7b5e9eb2c]
[fv-az1444-322:06690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7b5e4527e]
[fv-az1444-322:06690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7b5e288ff]
[fv-az1444-322:06690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7b62a5ff5]
[fv-az1444-322:06690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7b62bb0da]
[fv-az1444-322:06690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7b62a5a55]
[fv-az1444-322:06690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7b62a5a6f]
[fv-az1444-322:06690] [ 8] plumed_master(+0x146dd)[0x5572ba1676dd]
[fv-az1444-322:06690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7b5e2a1ca]
[fv-az1444-322:06690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7b5e2a28b]
[fv-az1444-322:06690] [11] plumed_master(+0x15365)[0x5572ba168365]
[fv-az1444-322:06690] *** End of error message ***
</pre>
{% endraw %}
