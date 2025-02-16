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
[fv-az1937-158:61261] *** Process received signal ***
[fv-az1937-158:61261] Signal: Aborted (6)
[fv-az1937-158:61261] Signal code:  (-6)
[fv-az1937-158:61261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5059a45330]
[fv-az1937-158:61261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5059a9eb2c]
[fv-az1937-158:61261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5059a4527e]
[fv-az1937-158:61261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5059a288ff]
[fv-az1937-158:61261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5059ea5ff5]
[fv-az1937-158:61261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5059ebb0da]
[fv-az1937-158:61261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5059ea5a55]
[fv-az1937-158:61261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5059ea5a6f]
[fv-az1937-158:61261] [ 8] plumed_master(+0x146dd)[0x55bf8f4566dd]
[fv-az1937-158:61261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5059a2a1ca]
[fv-az1937-158:61261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5059a2a28b]
[fv-az1937-158:61261] [11] plumed_master(+0x15365)[0x55bf8f457365]
[fv-az1937-158:61261] *** End of error message ***
</pre>
{% endraw %}
