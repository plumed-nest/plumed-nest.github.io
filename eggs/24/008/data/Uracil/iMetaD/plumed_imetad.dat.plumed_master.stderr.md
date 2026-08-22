**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervm76f27:07627] *** Process received signal ***
[runnervm76f27:07627] Signal: Aborted (6)
[runnervm76f27:07627] Signal code:  (-6)
[runnervm76f27:07627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f721ce45330]
[runnervm76f27:07627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f721ce9ec0c]
[runnervm76f27:07627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f721ce4527e]
[runnervm76f27:07627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f721ce288ff]
[runnervm76f27:07627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f721d2a5ff5]
[runnervm76f27:07627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f721d2bb0da]
[runnervm76f27:07627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f721d2a5a55]
[runnervm76f27:07627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f721d2a5a6f]
[runnervm76f27:07627] [ 8] plumed_master(+0x146dd)[0x564c0d9c86dd]
[runnervm76f27:07627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f721ce2a1ca]
[runnervm76f27:07627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f721ce2a28b]
[runnervm76f27:07627] [11] plumed_master(+0x15365)[0x564c0d9c9365]
[runnervm76f27:07627] *** End of error message ***
</pre>
{% endraw %}
