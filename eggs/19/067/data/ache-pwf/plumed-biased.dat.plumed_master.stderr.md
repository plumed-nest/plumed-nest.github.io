**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervm76f27:11303] *** Process received signal ***
[runnervm76f27:11303] Signal: Aborted (6)
[runnervm76f27:11303] Signal code:  (-6)
[runnervm76f27:11303] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f787e845330]
[runnervm76f27:11303] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f787e89ec0c]
[runnervm76f27:11303] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f787e84527e]
[runnervm76f27:11303] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f787e8288ff]
[runnervm76f27:11303] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f787eca5ff5]
[runnervm76f27:11303] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f787ecbb0da]
[runnervm76f27:11303] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f787eca5a55]
[runnervm76f27:11303] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f787eca5a6f]
[runnervm76f27:11303] [ 8] plumed_master(+0x146dd)[0x559f2a1406dd]
[runnervm76f27:11303] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f787e82a1ca]
[runnervm76f27:11303] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f787e82a28b]
[runnervm76f27:11303] [11] plumed_master(+0x15365)[0x559f2a141365]
[runnervm76f27:11303] *** End of error message ***
</pre>
{% endraw %}
