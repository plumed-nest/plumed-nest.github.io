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
[pkrvmberfyhpb9w:06476] *** Process received signal ***
[pkrvmberfyhpb9w:06476] Signal: Aborted (6)
[pkrvmberfyhpb9w:06476] Signal code:  (-6)
[pkrvmberfyhpb9w:06476] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55c8045330]
[pkrvmberfyhpb9w:06476] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55c809eb2c]
[pkrvmberfyhpb9w:06476] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55c804527e]
[pkrvmberfyhpb9w:06476] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55c80288ff]
[pkrvmberfyhpb9w:06476] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55c84a5ff5]
[pkrvmberfyhpb9w:06476] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55c84bb0da]
[pkrvmberfyhpb9w:06476] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55c84a5a55]
[pkrvmberfyhpb9w:06476] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55c84a5a6f]
[pkrvmberfyhpb9w:06476] [ 8] plumed(+0x146dd)[0x55ec469916dd]
[pkrvmberfyhpb9w:06476] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55c802a1ca]
[pkrvmberfyhpb9w:06476] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55c802a28b]
[pkrvmberfyhpb9w:06476] [11] plumed(+0x15365)[0x55ec46992365]
[pkrvmberfyhpb9w:06476] *** End of error message ***
</pre>
{% endraw %}
