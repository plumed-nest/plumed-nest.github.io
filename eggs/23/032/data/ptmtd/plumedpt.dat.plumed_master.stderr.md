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
[runnervmvrwv9:06984] *** Process received signal ***
[runnervmvrwv9:06984] Signal: Aborted (6)
[runnervmvrwv9:06984] Signal code:  (-6)
[runnervmvrwv9:06984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2984845330]
[runnervmvrwv9:06984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f298489eb2c]
[runnervmvrwv9:06984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f298484527e]
[runnervmvrwv9:06984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29848288ff]
[runnervmvrwv9:06984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2984ca5ff5]
[runnervmvrwv9:06984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2984cbb0da]
[runnervmvrwv9:06984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2984ca5a55]
[runnervmvrwv9:06984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2984ca5a6f]
[runnervmvrwv9:06984] [ 8] plumed_master(+0x146dd)[0x565425a6d6dd]
[runnervmvrwv9:06984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f298482a1ca]
[runnervmvrwv9:06984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f298482a28b]
[runnervmvrwv9:06984] [11] plumed_master(+0x15365)[0x565425a6e365]
[runnervmvrwv9:06984] *** End of error message ***
</pre>
{% endraw %}
