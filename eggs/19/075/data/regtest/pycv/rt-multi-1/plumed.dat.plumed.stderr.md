**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm76f27:10898] *** Process received signal ***
[runnervm76f27:10898] Signal: Aborted (6)
[runnervm76f27:10898] Signal code:  (-6)
[runnervm76f27:10898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb011245330]
[runnervm76f27:10898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb01129ec0c]
[runnervm76f27:10898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb01124527e]
[runnervm76f27:10898] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0112288ff]
[runnervm76f27:10898] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0116a5ff5]
[runnervm76f27:10898] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0116bb0da]
[runnervm76f27:10898] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0116a5a55]
[runnervm76f27:10898] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0116a5a6f]
[runnervm76f27:10898] [ 8] plumed(+0x146dd)[0x562f9d4786dd]
[runnervm76f27:10898] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb01122a1ca]
[runnervm76f27:10898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb01122a28b]
[runnervm76f27:10898] [11] plumed(+0x15365)[0x562f9d479365]
[runnervm76f27:10898] *** End of error message ***
</pre>
{% endraw %}
