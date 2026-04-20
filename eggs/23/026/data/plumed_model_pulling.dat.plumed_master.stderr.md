**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:05868] *** Process received signal ***
[runnervmeorf1:05868] Signal: Aborted (6)
[runnervmeorf1:05868] Signal code:  (-6)
[runnervmeorf1:05868] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc793645330]
[runnervmeorf1:05868] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc79369eb2c]
[runnervmeorf1:05868] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc79364527e]
[runnervmeorf1:05868] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7936288ff]
[runnervmeorf1:05868] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc793aa5ff5]
[runnervmeorf1:05868] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc793abb0da]
[runnervmeorf1:05868] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc793aa5a55]
[runnervmeorf1:05868] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc793aa5a6f]
[runnervmeorf1:05868] [ 8] plumed_master(+0x146dd)[0x562b268826dd]
[runnervmeorf1:05868] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc79362a1ca]
[runnervmeorf1:05868] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc79362a28b]
[runnervmeorf1:05868] [11] plumed_master(+0x15365)[0x562b26883365]
[runnervmeorf1:05868] *** End of error message ***
</pre>
{% endraw %}
