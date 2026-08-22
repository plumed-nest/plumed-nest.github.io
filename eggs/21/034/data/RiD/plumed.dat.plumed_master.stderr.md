**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervm76f27:09959] *** Process received signal ***
[runnervm76f27:09959] Signal: Aborted (6)
[runnervm76f27:09959] Signal code:  (-6)
[runnervm76f27:09959] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f923b645330]
[runnervm76f27:09959] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f923b69ec0c]
[runnervm76f27:09959] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f923b64527e]
[runnervm76f27:09959] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f923b6288ff]
[runnervm76f27:09959] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f923baa5ff5]
[runnervm76f27:09959] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f923babb0da]
[runnervm76f27:09959] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f923baa5a55]
[runnervm76f27:09959] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f923baa5a6f]
[runnervm76f27:09959] [ 8] plumed_master(+0x146dd)[0x55ada86ca6dd]
[runnervm76f27:09959] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f923b62a1ca]
[runnervm76f27:09959] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f923b62a28b]
[runnervm76f27:09959] [11] plumed_master(+0x15365)[0x55ada86cb365]
[runnervm76f27:09959] *** End of error message ***
</pre>
{% endraw %}
