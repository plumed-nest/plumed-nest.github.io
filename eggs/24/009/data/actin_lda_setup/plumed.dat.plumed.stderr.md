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
[fv-az1278-681:61572] *** Process received signal ***
[fv-az1278-681:61572] Signal: Aborted (6)
[fv-az1278-681:61572] Signal code:  (-6)
[fv-az1278-681:61572] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac42e45330]
[fv-az1278-681:61572] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac42e9eb2c]
[fv-az1278-681:61572] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac42e4527e]
[fv-az1278-681:61572] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac42e288ff]
[fv-az1278-681:61572] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac432a5ff5]
[fv-az1278-681:61572] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac432bb0da]
[fv-az1278-681:61572] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac432a5a55]
[fv-az1278-681:61572] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac432a5a6f]
[fv-az1278-681:61572] [ 8] plumed(+0x146dd)[0x56484e6d26dd]
[fv-az1278-681:61572] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac42e2a1ca]
[fv-az1278-681:61572] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac42e2a28b]
[fv-az1278-681:61572] [11] plumed(+0x15365)[0x56484e6d3365]
[fv-az1278-681:61572] *** End of error message ***
</pre>
{% endraw %}
