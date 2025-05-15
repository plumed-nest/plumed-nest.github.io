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
[pkrvmberfyhpb9w:06492] *** Process received signal ***
[pkrvmberfyhpb9w:06492] Signal: Aborted (6)
[pkrvmberfyhpb9w:06492] Signal code:  (-6)
[pkrvmberfyhpb9w:06492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe75a845330]
[pkrvmberfyhpb9w:06492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe75a89eb2c]
[pkrvmberfyhpb9w:06492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe75a84527e]
[pkrvmberfyhpb9w:06492] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe75a8288ff]
[pkrvmberfyhpb9w:06492] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe75aca5ff5]
[pkrvmberfyhpb9w:06492] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe75acbb0da]
[pkrvmberfyhpb9w:06492] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe75aca5a55]
[pkrvmberfyhpb9w:06492] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe75aca5a6f]
[pkrvmberfyhpb9w:06492] [ 8] plumed_master(+0x146dd)[0x561df76376dd]
[pkrvmberfyhpb9w:06492] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe75a82a1ca]
[pkrvmberfyhpb9w:06492] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe75a82a28b]
[pkrvmberfyhpb9w:06492] [11] plumed_master(+0x15365)[0x561df7638365]
[pkrvmberfyhpb9w:06492] *** End of error message ***
</pre>
{% endraw %}
