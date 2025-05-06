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
[fv-az1278-681:61587] *** Process received signal ***
[fv-az1278-681:61587] Signal: Aborted (6)
[fv-az1278-681:61587] Signal code:  (-6)
[fv-az1278-681:61587] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5ac2045330]
[fv-az1278-681:61587] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5ac209eb2c]
[fv-az1278-681:61587] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5ac204527e]
[fv-az1278-681:61587] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5ac20288ff]
[fv-az1278-681:61587] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5ac24a5ff5]
[fv-az1278-681:61587] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5ac24bb0da]
[fv-az1278-681:61587] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5ac24a5a55]
[fv-az1278-681:61587] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5ac24a5a6f]
[fv-az1278-681:61587] [ 8] plumed_master(+0x146dd)[0x557e156d36dd]
[fv-az1278-681:61587] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5ac202a1ca]
[fv-az1278-681:61587] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5ac202a28b]
[fv-az1278-681:61587] [11] plumed_master(+0x15365)[0x557e156d4365]
[fv-az1278-681:61587] *** End of error message ***
</pre>
{% endraw %}
