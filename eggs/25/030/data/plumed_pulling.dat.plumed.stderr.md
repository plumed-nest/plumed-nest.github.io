**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_pulling.dat   
Download: [zipped raw stdout](plumed_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:04219] *** Process received signal ***
[runnervmeorf1:04219] Signal: Aborted (6)
[runnervmeorf1:04219] Signal code:  (-6)
[runnervmeorf1:04219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f60ada45330]
[runnervmeorf1:04219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f60ada9eb2c]
[runnervmeorf1:04219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f60ada4527e]
[runnervmeorf1:04219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60ada288ff]
[runnervmeorf1:04219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60adea5ff5]
[runnervmeorf1:04219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60adebb0da]
[runnervmeorf1:04219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60adea5a55]
[runnervmeorf1:04219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60adea5a6f]
[runnervmeorf1:04219] [ 8] plumed(+0x146dd)[0x55c024e746dd]
[runnervmeorf1:04219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f60ada2a1ca]
[runnervmeorf1:04219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f60ada2a28b]
[runnervmeorf1:04219] [11] plumed(+0x15365)[0x55c024e75365]
[runnervmeorf1:04219] *** End of error message ***
</pre>
{% endraw %}
