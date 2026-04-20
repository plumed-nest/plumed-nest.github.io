**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w11-s3.468/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10390] *** Process received signal ***
[runnervmeorf1:10390] Signal: Aborted (6)
[runnervmeorf1:10390] Signal code:  (-6)
[runnervmeorf1:10390] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7a8f645330]
[runnervmeorf1:10390] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7a8f69eb2c]
[runnervmeorf1:10390] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7a8f64527e]
[runnervmeorf1:10390] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7a8f6288ff]
[runnervmeorf1:10390] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7a8faa5ff5]
[runnervmeorf1:10390] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7a8fabb0da]
[runnervmeorf1:10390] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7a8faa5a55]
[runnervmeorf1:10390] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7a8faa5a6f]
[runnervmeorf1:10390] [ 8] plumed(+0x146dd)[0x565237ea76dd]
[runnervmeorf1:10390] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7a8f62a1ca]
[runnervmeorf1:10390] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7a8f62a28b]
[runnervmeorf1:10390] [11] plumed(+0x15365)[0x565237ea8365]
[runnervmeorf1:10390] *** End of error message ***
</pre>
{% endraw %}
