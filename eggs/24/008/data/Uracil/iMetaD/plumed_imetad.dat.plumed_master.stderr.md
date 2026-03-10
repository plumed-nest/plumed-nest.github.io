**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervm0kj6c:06342] *** Process received signal ***
[runnervm0kj6c:06342] Signal: Aborted (6)
[runnervm0kj6c:06342] Signal code:  (-6)
[runnervm0kj6c:06342] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbd55c45330]
[runnervm0kj6c:06342] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbd55c9eb2c]
[runnervm0kj6c:06342] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbd55c4527e]
[runnervm0kj6c:06342] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbd55c288ff]
[runnervm0kj6c:06342] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbd560a5ff5]
[runnervm0kj6c:06342] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbd560bb0da]
[runnervm0kj6c:06342] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbd560a5a55]
[runnervm0kj6c:06342] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbd560a5a6f]
[runnervm0kj6c:06342] [ 8] plumed_master(+0x146dd)[0x55b344cdc6dd]
[runnervm0kj6c:06342] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbd55c2a1ca]
[runnervm0kj6c:06342] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbd55c2a28b]
[runnervm0kj6c:06342] [11] plumed_master(+0x15365)[0x55b344cdd365]
[runnervm0kj6c:06342] *** End of error message ***
</pre>
{% endraw %}
