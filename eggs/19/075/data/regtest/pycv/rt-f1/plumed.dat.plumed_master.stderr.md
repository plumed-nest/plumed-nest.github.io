**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervm76f27:10659] *** Process received signal ***
[runnervm76f27:10659] Signal: Aborted (6)
[runnervm76f27:10659] Signal code:  (-6)
[runnervm76f27:10659] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a32245330]
[runnervm76f27:10659] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a3229ec0c]
[runnervm76f27:10659] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a3224527e]
[runnervm76f27:10659] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a322288ff]
[runnervm76f27:10659] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a326a5ff5]
[runnervm76f27:10659] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a326bb0da]
[runnervm76f27:10659] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a326a5a55]
[runnervm76f27:10659] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a326a5a6f]
[runnervm76f27:10659] [ 8] plumed_master(+0x146dd)[0x5593b242e6dd]
[runnervm76f27:10659] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a3222a1ca]
[runnervm76f27:10659] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a3222a28b]
[runnervm76f27:10659] [11] plumed_master(+0x15365)[0x5593b242f365]
[runnervm76f27:10659] *** End of error message ***
</pre>
{% endraw %}
