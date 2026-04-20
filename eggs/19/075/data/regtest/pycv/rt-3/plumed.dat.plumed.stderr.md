**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:09644] *** Process received signal ***
[runnervmeorf1:09644] Signal: Aborted (6)
[runnervmeorf1:09644] Signal code:  (-6)
[runnervmeorf1:09644] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0949245330]
[runnervmeorf1:09644] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f094929eb2c]
[runnervmeorf1:09644] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f094924527e]
[runnervmeorf1:09644] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09492288ff]
[runnervmeorf1:09644] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f09496a5ff5]
[runnervmeorf1:09644] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f09496bb0da]
[runnervmeorf1:09644] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f09496a5a55]
[runnervmeorf1:09644] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f09496a5a6f]
[runnervmeorf1:09644] [ 8] plumed(+0x146dd)[0x555fff7ff6dd]
[runnervmeorf1:09644] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f094922a1ca]
[runnervmeorf1:09644] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f094922a28b]
[runnervmeorf1:09644] [11] plumed(+0x15365)[0x555fff800365]
[runnervmeorf1:09644] *** End of error message ***
</pre>
{% endraw %}
