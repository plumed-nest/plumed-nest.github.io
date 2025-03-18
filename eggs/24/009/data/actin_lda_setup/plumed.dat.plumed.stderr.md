**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[fv-az1377-740:61092] *** Process received signal ***
[fv-az1377-740:61092] Signal: Aborted (6)
[fv-az1377-740:61092] Signal code:  (-6)
[fv-az1377-740:61092] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6263045330]
[fv-az1377-740:61092] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f626309eb2c]
[fv-az1377-740:61092] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f626304527e]
[fv-az1377-740:61092] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62630288ff]
[fv-az1377-740:61092] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62634a5ff5]
[fv-az1377-740:61092] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62634bb0da]
[fv-az1377-740:61092] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62634a5a55]
[fv-az1377-740:61092] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62634a5a6f]
[fv-az1377-740:61092] [ 8] plumed(+0x146dd)[0x562d699d76dd]
[fv-az1377-740:61092] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f626302a1ca]
[fv-az1377-740:61092] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f626302a28b]
[fv-az1377-740:61092] [11] plumed(+0x15365)[0x562d699d8365]
[fv-az1377-740:61092] *** End of error message ***
</pre>
{% endraw %}
