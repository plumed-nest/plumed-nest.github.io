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
[pkrvmpptgkbjq6m:07667] *** Process received signal ***
[pkrvmpptgkbjq6m:07667] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07667] Signal code:  (-6)
[pkrvmpptgkbjq6m:07667] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3bf8245330]
[pkrvmpptgkbjq6m:07667] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3bf829eb2c]
[pkrvmpptgkbjq6m:07667] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3bf824527e]
[pkrvmpptgkbjq6m:07667] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3bf82288ff]
[pkrvmpptgkbjq6m:07667] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3bf86a5ff5]
[pkrvmpptgkbjq6m:07667] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3bf86bb0da]
[pkrvmpptgkbjq6m:07667] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3bf86a5a55]
[pkrvmpptgkbjq6m:07667] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3bf86a5a6f]
[pkrvmpptgkbjq6m:07667] [ 8] plumed(+0x146dd)[0x560b3e5026dd]
[pkrvmpptgkbjq6m:07667] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3bf822a1ca]
[pkrvmpptgkbjq6m:07667] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3bf822a28b]
[pkrvmpptgkbjq6m:07667] [11] plumed(+0x15365)[0x560b3e503365]
[pkrvmpptgkbjq6m:07667] *** End of error message ***
</pre>
{% endraw %}
