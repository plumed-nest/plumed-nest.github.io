**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervm76f27:05421] *** Process received signal ***
[runnervm76f27:05421] Signal: Aborted (6)
[runnervm76f27:05421] Signal code:  (-6)
[runnervm76f27:05421] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d26045330]
[runnervm76f27:05421] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d2609ec0c]
[runnervm76f27:05421] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d2604527e]
[runnervm76f27:05421] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d260288ff]
[runnervm76f27:05421] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d264a5ff5]
[runnervm76f27:05421] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d264bb0da]
[runnervm76f27:05421] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d264a5a55]
[runnervm76f27:05421] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d264a5a6f]
[runnervm76f27:05421] [ 8] plumed_master(+0x146dd)[0x56071cf856dd]
[runnervm76f27:05421] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d2602a1ca]
[runnervm76f27:05421] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d2602a28b]
[runnervm76f27:05421] [11] plumed_master(+0x15365)[0x56071cf86365]
[runnervm76f27:05421] *** End of error message ***
</pre>
{% endraw %}
