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
[fv-az1657-925:06403] *** Process received signal ***
[fv-az1657-925:06403] Signal: Aborted (6)
[fv-az1657-925:06403] Signal code:  (-6)
[fv-az1657-925:06403] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f635d245330]
[fv-az1657-925:06403] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f635d29eb2c]
[fv-az1657-925:06403] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f635d24527e]
[fv-az1657-925:06403] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f635d2288ff]
[fv-az1657-925:06403] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f635d6a5ff5]
[fv-az1657-925:06403] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f635d6bb0da]
[fv-az1657-925:06403] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f635d6a5a55]
[fv-az1657-925:06403] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f635d6a5a6f]
[fv-az1657-925:06403] [ 8] plumed_master(+0x146dd)[0x55c10b15b6dd]
[fv-az1657-925:06403] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f635d22a1ca]
[fv-az1657-925:06403] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f635d22a28b]
[fv-az1657-925:06403] [11] plumed_master(+0x15365)[0x55c10b15c365]
[fv-az1657-925:06403] *** End of error message ***
</pre>
{% endraw %}
