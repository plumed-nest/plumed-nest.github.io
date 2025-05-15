**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvmberfyhpb9w:06715] *** Process received signal ***
[pkrvmberfyhpb9w:06715] Signal: Aborted (6)
[pkrvmberfyhpb9w:06715] Signal code:  (-6)
[pkrvmberfyhpb9w:06715] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c63645330]
[pkrvmberfyhpb9w:06715] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c6369eb2c]
[pkrvmberfyhpb9w:06715] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c6364527e]
[pkrvmberfyhpb9w:06715] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c636288ff]
[pkrvmberfyhpb9w:06715] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c63aa5ff5]
[pkrvmberfyhpb9w:06715] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c63abb0da]
[pkrvmberfyhpb9w:06715] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c63aa5a55]
[pkrvmberfyhpb9w:06715] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c63aa5a6f]
[pkrvmberfyhpb9w:06715] [ 8] plumed(+0x146dd)[0x556918a786dd]
[pkrvmberfyhpb9w:06715] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c6362a1ca]
[pkrvmberfyhpb9w:06715] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c6362a28b]
[pkrvmberfyhpb9w:06715] [11] plumed(+0x15365)[0x556918a79365]
[pkrvmberfyhpb9w:06715] *** End of error message ***
</pre>
{% endraw %}
