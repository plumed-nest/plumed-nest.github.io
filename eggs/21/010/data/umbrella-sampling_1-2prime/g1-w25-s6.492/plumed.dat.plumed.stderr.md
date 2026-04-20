**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:11164] *** Process received signal ***
[runnervmeorf1:11164] Signal: Aborted (6)
[runnervmeorf1:11164] Signal code:  (-6)
[runnervmeorf1:11164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed84445330]
[runnervmeorf1:11164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed8449eb2c]
[runnervmeorf1:11164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed8444527e]
[runnervmeorf1:11164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed844288ff]
[runnervmeorf1:11164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed848a5ff5]
[runnervmeorf1:11164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed848bb0da]
[runnervmeorf1:11164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed848a5a55]
[runnervmeorf1:11164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed848a5a6f]
[runnervmeorf1:11164] [ 8] plumed(+0x146dd)[0x55811d49e6dd]
[runnervmeorf1:11164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed8442a1ca]
[runnervmeorf1:11164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed8442a28b]
[runnervmeorf1:11164] [11] plumed(+0x15365)[0x55811d49f365]
[runnervmeorf1:11164] *** End of error message ***
</pre>
{% endraw %}
