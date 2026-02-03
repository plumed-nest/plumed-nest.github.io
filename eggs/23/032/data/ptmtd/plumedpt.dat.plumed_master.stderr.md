**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[runnervmkj6or:05488] *** Process received signal ***
[runnervmkj6or:05488] Signal: Aborted (6)
[runnervmkj6or:05488] Signal code:  (-6)
[runnervmkj6or:05488] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb9b2045330]
[runnervmkj6or:05488] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb9b209eb2c]
[runnervmkj6or:05488] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb9b204527e]
[runnervmkj6or:05488] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9b20288ff]
[runnervmkj6or:05488] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9b24a5ff5]
[runnervmkj6or:05488] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9b24bb0da]
[runnervmkj6or:05488] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9b24a5a55]
[runnervmkj6or:05488] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9b24a5a6f]
[runnervmkj6or:05488] [ 8] plumed_master(+0x146dd)[0x55cf0c4ba6dd]
[runnervmkj6or:05488] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb9b202a1ca]
[runnervmkj6or:05488] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb9b202a28b]
[runnervmkj6or:05488] [11] plumed_master(+0x15365)[0x55cf0c4bb365]
[runnervmkj6or:05488] *** End of error message ***
</pre>
{% endraw %}
