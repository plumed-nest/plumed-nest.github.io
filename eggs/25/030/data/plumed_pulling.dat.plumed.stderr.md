**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_pulling.dat   
Download: [zipped raw stdout](plumed_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm76f27:05304] *** Process received signal ***
[runnervm76f27:05304] Signal: Aborted (6)
[runnervm76f27:05304] Signal code:  (-6)
[runnervm76f27:05304] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6eea445330]
[runnervm76f27:05304] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6eea49ec0c]
[runnervm76f27:05304] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6eea44527e]
[runnervm76f27:05304] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6eea4288ff]
[runnervm76f27:05304] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6eea8a5ff5]
[runnervm76f27:05304] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6eea8bb0da]
[runnervm76f27:05304] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6eea8a5a55]
[runnervm76f27:05304] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6eea8a5a6f]
[runnervm76f27:05304] [ 8] plumed(+0x146dd)[0x562ed2d116dd]
[runnervm76f27:05304] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6eea42a1ca]
[runnervm76f27:05304] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6eea42a28b]
[runnervm76f27:05304] [11] plumed(+0x15365)[0x562ed2d12365]
[runnervm76f27:05304] *** End of error message ***
</pre>
{% endraw %}
