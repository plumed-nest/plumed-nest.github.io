**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervm76f27:06092] *** Process received signal ***
[runnervm76f27:06092] Signal: Aborted (6)
[runnervm76f27:06092] Signal code:  (-6)
[runnervm76f27:06092] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fc8645330]
[runnervm76f27:06092] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fc869ec0c]
[runnervm76f27:06092] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fc864527e]
[runnervm76f27:06092] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fc86288ff]
[runnervm76f27:06092] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fc8aa5ff5]
[runnervm76f27:06092] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fc8abb0da]
[runnervm76f27:06092] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fc8aa5a55]
[runnervm76f27:06092] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fc8aa5a6f]
[runnervm76f27:06092] [ 8] plumed(+0x146dd)[0x55db4b22d6dd]
[runnervm76f27:06092] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fc862a1ca]
[runnervm76f27:06092] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fc862a28b]
[runnervm76f27:06092] [11] plumed(+0x15365)[0x55db4b22e365]
[runnervm76f27:06092] *** End of error message ***
</pre>
{% endraw %}
