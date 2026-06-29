**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmmklqx:05373] *** Process received signal ***
[runnervmmklqx:05373] Signal: Aborted (6)
[runnervmmklqx:05373] Signal code:  (-6)
[runnervmmklqx:05373] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9f30845330]
[runnervmmklqx:05373] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9f3089eb2c]
[runnervmmklqx:05373] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9f3084527e]
[runnervmmklqx:05373] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9f308288ff]
[runnervmmklqx:05373] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9f30ca5ff5]
[runnervmmklqx:05373] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9f30cbb0da]
[runnervmmklqx:05373] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9f30ca5a55]
[runnervmmklqx:05373] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9f30ca5a6f]
[runnervmmklqx:05373] [ 8] plumed_master(+0x146dd)[0x5596506ca6dd]
[runnervmmklqx:05373] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9f3082a1ca]
[runnervmmklqx:05373] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9f3082a28b]
[runnervmmklqx:05373] [11] plumed_master(+0x15365)[0x5596506cb365]
[runnervmmklqx:05373] *** End of error message ***
</pre>
{% endraw %}
