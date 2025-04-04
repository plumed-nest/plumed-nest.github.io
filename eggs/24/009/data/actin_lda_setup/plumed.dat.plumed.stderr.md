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
[fv-az805-507:07549] *** Process received signal ***
[fv-az805-507:07549] Signal: Aborted (6)
[fv-az805-507:07549] Signal code:  (-6)
[fv-az805-507:07549] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7587a45330]
[fv-az805-507:07549] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7587a9eb2c]
[fv-az805-507:07549] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7587a4527e]
[fv-az805-507:07549] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7587a288ff]
[fv-az805-507:07549] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7587ea5ff5]
[fv-az805-507:07549] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7587ebb0da]
[fv-az805-507:07549] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7587ea5a55]
[fv-az805-507:07549] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7587ea5a6f]
[fv-az805-507:07549] [ 8] plumed(+0x146dd)[0x5645e7c636dd]
[fv-az805-507:07549] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7587a2a1ca]
[fv-az805-507:07549] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7587a2a28b]
[fv-az805-507:07549] [11] plumed(+0x15365)[0x5645e7c64365]
[fv-az805-507:07549] *** End of error message ***
</pre>
{% endraw %}
