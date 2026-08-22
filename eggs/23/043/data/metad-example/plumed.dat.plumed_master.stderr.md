**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervm76f27:06592] *** Process received signal ***
[runnervm76f27:06592] Signal: Aborted (6)
[runnervm76f27:06592] Signal code:  (-6)
[runnervm76f27:06592] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efc6f645330]
[runnervm76f27:06592] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efc6f69ec0c]
[runnervm76f27:06592] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efc6f64527e]
[runnervm76f27:06592] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efc6f6288ff]
[runnervm76f27:06592] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efc6faa5ff5]
[runnervm76f27:06592] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efc6fabb0da]
[runnervm76f27:06592] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efc6faa5a55]
[runnervm76f27:06592] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efc6faa5a6f]
[runnervm76f27:06592] [ 8] plumed_master(+0x146dd)[0x559ba582e6dd]
[runnervm76f27:06592] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efc6f62a1ca]
[runnervm76f27:06592] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efc6f62a28b]
[runnervm76f27:06592] [11] plumed_master(+0x15365)[0x559ba582f365]
[runnervm76f27:06592] *** End of error message ***
</pre>
{% endraw %}
