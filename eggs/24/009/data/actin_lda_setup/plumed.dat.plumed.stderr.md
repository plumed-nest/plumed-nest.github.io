**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmmklqx:06374] *** Process received signal ***
[runnervmmklqx:06374] Signal: Aborted (6)
[runnervmmklqx:06374] Signal code:  (-6)
[runnervmmklqx:06374] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabad445330]
[runnervmmklqx:06374] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabad49eb2c]
[runnervmmklqx:06374] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabad44527e]
[runnervmmklqx:06374] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabad4288ff]
[runnervmmklqx:06374] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabad8a5ff5]
[runnervmmklqx:06374] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabad8bb0da]
[runnervmmklqx:06374] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabad8a5a55]
[runnervmmklqx:06374] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabad8a5a6f]
[runnervmmklqx:06374] [ 8] plumed(+0x146dd)[0x55c1a96786dd]
[runnervmmklqx:06374] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabad42a1ca]
[runnervmmklqx:06374] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabad42a28b]
[runnervmmklqx:06374] [11] plumed(+0x15365)[0x55c1a9679365]
[runnervmmklqx:06374] *** End of error message ***
</pre>
{% endraw %}
