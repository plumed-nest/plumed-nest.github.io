**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmeorf1:05851] *** Process received signal ***
[runnervmeorf1:05851] Signal: Aborted (6)
[runnervmeorf1:05851] Signal code:  (-6)
[runnervmeorf1:05851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3610a45330]
[runnervmeorf1:05851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3610a9eb2c]
[runnervmeorf1:05851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3610a4527e]
[runnervmeorf1:05851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3610a288ff]
[runnervmeorf1:05851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3610ea5ff5]
[runnervmeorf1:05851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3610ebb0da]
[runnervmeorf1:05851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3610ea5a55]
[runnervmeorf1:05851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3610ea5a6f]
[runnervmeorf1:05851] [ 8] plumed(+0x146dd)[0x5604d68346dd]
[runnervmeorf1:05851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3610a2a1ca]
[runnervmeorf1:05851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3610a2a28b]
[runnervmeorf1:05851] [11] plumed(+0x15365)[0x5604d6835365]
[runnervmeorf1:05851] *** End of error message ***
</pre>
{% endraw %}
