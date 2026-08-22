**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervm76f27:10710] *** Process received signal ***
[runnervm76f27:10710] Signal: Aborted (6)
[runnervm76f27:10710] Signal code:  (-6)
[runnervm76f27:10710] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf21845330]
[runnervm76f27:10710] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf2189ec0c]
[runnervm76f27:10710] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf2184527e]
[runnervm76f27:10710] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf218288ff]
[runnervm76f27:10710] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf21ca5ff5]
[runnervm76f27:10710] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf21cbb0da]
[runnervm76f27:10710] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf21ca5a55]
[runnervm76f27:10710] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf21ca5a6f]
[runnervm76f27:10710] [ 8] plumed_master(+0x146dd)[0x5636048a96dd]
[runnervm76f27:10710] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf2182a1ca]
[runnervm76f27:10710] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf2182a28b]
[runnervm76f27:10710] [11] plumed_master(+0x15365)[0x5636048aa365]
[runnervm76f27:10710] *** End of error message ***
</pre>
{% endraw %}
