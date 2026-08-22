**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervm76f27:04581] *** Process received signal ***
[runnervm76f27:04581] Signal: Aborted (6)
[runnervm76f27:04581] Signal code:  (-6)
[runnervm76f27:04581] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa306045330]
[runnervm76f27:04581] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa30609ec0c]
[runnervm76f27:04581] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa30604527e]
[runnervm76f27:04581] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3060288ff]
[runnervm76f27:04581] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3064a5ff5]
[runnervm76f27:04581] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3064bb0da]
[runnervm76f27:04581] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3064a5a55]
[runnervm76f27:04581] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3064a5a6f]
[runnervm76f27:04581] [ 8] plumed_master(+0x146dd)[0x5590191896dd]
[runnervm76f27:04581] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa30602a1ca]
[runnervm76f27:04581] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa30602a28b]
[runnervm76f27:04581] [11] plumed_master(+0x15365)[0x55901918a365]
[runnervm76f27:04581] *** End of error message ***
</pre>
{% endraw %}
