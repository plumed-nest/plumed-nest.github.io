**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervm76f27:07312] *** Process received signal ***
[runnervm76f27:07312] Signal: Aborted (6)
[runnervm76f27:07312] Signal code:  (-6)
[runnervm76f27:07312] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fecbd245330]
[runnervm76f27:07312] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fecbd29ec0c]
[runnervm76f27:07312] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fecbd24527e]
[runnervm76f27:07312] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fecbd2288ff]
[runnervm76f27:07312] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fecbd6a5ff5]
[runnervm76f27:07312] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fecbd6bb0da]
[runnervm76f27:07312] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fecbd6a5a55]
[runnervm76f27:07312] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fecbd6a5a6f]
[runnervm76f27:07312] [ 8] plumed_master(+0x146dd)[0x559cd078d6dd]
[runnervm76f27:07312] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fecbd22a1ca]
[runnervm76f27:07312] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fecbd22a28b]
[runnervm76f27:07312] [11] plumed_master(+0x15365)[0x559cd078e365]
[runnervm76f27:07312] *** End of error message ***
</pre>
{% endraw %}
