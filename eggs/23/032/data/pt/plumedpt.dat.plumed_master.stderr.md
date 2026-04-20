**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmeorf1:05868] *** Process received signal ***
[runnervmeorf1:05868] Signal: Aborted (6)
[runnervmeorf1:05868] Signal code:  (-6)
[runnervmeorf1:05868] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0738e45330]
[runnervmeorf1:05868] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0738e9eb2c]
[runnervmeorf1:05868] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0738e4527e]
[runnervmeorf1:05868] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0738e288ff]
[runnervmeorf1:05868] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07392a5ff5]
[runnervmeorf1:05868] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07392bb0da]
[runnervmeorf1:05868] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07392a5a55]
[runnervmeorf1:05868] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07392a5a6f]
[runnervmeorf1:05868] [ 8] plumed_master(+0x146dd)[0x55f1f6bb96dd]
[runnervmeorf1:05868] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0738e2a1ca]
[runnervmeorf1:05868] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0738e2a28b]
[runnervmeorf1:05868] [11] plumed_master(+0x15365)[0x55f1f6bba365]
[runnervmeorf1:05868] *** End of error message ***
</pre>
{% endraw %}
