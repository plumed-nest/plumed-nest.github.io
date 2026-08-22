**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervm76f27:11626] *** Process received signal ***
[runnervm76f27:11626] Signal: Aborted (6)
[runnervm76f27:11626] Signal code:  (-6)
[runnervm76f27:11626] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb797245330]
[runnervm76f27:11626] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb79729ec0c]
[runnervm76f27:11626] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb79724527e]
[runnervm76f27:11626] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7972288ff]
[runnervm76f27:11626] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7976a5ff5]
[runnervm76f27:11626] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7976bb0da]
[runnervm76f27:11626] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7976a5a55]
[runnervm76f27:11626] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7976a5a6f]
[runnervm76f27:11626] [ 8] plumed(+0x146dd)[0x557cece736dd]
[runnervm76f27:11626] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb79722a1ca]
[runnervm76f27:11626] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb79722a28b]
[runnervm76f27:11626] [11] plumed(+0x15365)[0x557cece74365]
[runnervm76f27:11626] *** End of error message ***
</pre>
{% endraw %}
