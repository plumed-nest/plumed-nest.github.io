**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmvrwv9:06915] *** Process received signal ***
[runnervmvrwv9:06915] Signal: Aborted (6)
[runnervmvrwv9:06915] Signal code:  (-6)
[runnervmvrwv9:06915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8d7845330]
[runnervmvrwv9:06915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8d789eb2c]
[runnervmvrwv9:06915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8d784527e]
[runnervmvrwv9:06915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8d78288ff]
[runnervmvrwv9:06915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8d7ca5ff5]
[runnervmvrwv9:06915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8d7cbb0da]
[runnervmvrwv9:06915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8d7ca5a55]
[runnervmvrwv9:06915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8d7ca5a6f]
[runnervmvrwv9:06915] [ 8] plumed(+0x146dd)[0x55fd8de5d6dd]
[runnervmvrwv9:06915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8d782a1ca]
[runnervmvrwv9:06915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8d782a28b]
[runnervmvrwv9:06915] [11] plumed(+0x15365)[0x55fd8de5e365]
[runnervmvrwv9:06915] *** End of error message ***
</pre>
{% endraw %}
