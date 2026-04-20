**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:05853] *** Process received signal ***
[runnervmeorf1:05853] Signal: Aborted (6)
[runnervmeorf1:05853] Signal code:  (-6)
[runnervmeorf1:05853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8ff045330]
[runnervmeorf1:05853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8ff09eb2c]
[runnervmeorf1:05853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8ff04527e]
[runnervmeorf1:05853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8ff0288ff]
[runnervmeorf1:05853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8ff4a5ff5]
[runnervmeorf1:05853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8ff4bb0da]
[runnervmeorf1:05853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8ff4a5a55]
[runnervmeorf1:05853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8ff4a5a6f]
[runnervmeorf1:05853] [ 8] plumed(+0x146dd)[0x562f57b366dd]
[runnervmeorf1:05853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8ff02a1ca]
[runnervmeorf1:05853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8ff02a28b]
[runnervmeorf1:05853] [11] plumed(+0x15365)[0x562f57b37365]
[runnervmeorf1:05853] *** End of error message ***
</pre>
{% endraw %}
