**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:09634] *** Process received signal ***
[runnervm76f27:09634] Signal: Aborted (6)
[runnervm76f27:09634] Signal code:  (-6)
[runnervm76f27:09634] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb212245330]
[runnervm76f27:09634] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb21229ec0c]
[runnervm76f27:09634] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb21224527e]
[runnervm76f27:09634] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2122288ff]
[runnervm76f27:09634] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2126a5ff5]
[runnervm76f27:09634] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2126bb0da]
[runnervm76f27:09634] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2126a5a55]
[runnervm76f27:09634] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2126a5a6f]
[runnervm76f27:09634] [ 8] plumed(+0x146dd)[0x55ad27de26dd]
[runnervm76f27:09634] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb21222a1ca]
[runnervm76f27:09634] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb21222a28b]
[runnervm76f27:09634] [11] plumed(+0x15365)[0x55ad27de3365]
[runnervm76f27:09634] *** End of error message ***
</pre>
{% endraw %}
