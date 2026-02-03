**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @19 : keyword ARG is compulsory for this action
[runnervmkj6or:09515] *** Process received signal ***
[runnervmkj6or:09515] Signal: Aborted (6)
[runnervmkj6or:09515] Signal code:  (-6)
[runnervmkj6or:09515] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fe4245330]
[runnervmkj6or:09515] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fe429eb2c]
[runnervmkj6or:09515] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fe424527e]
[runnervmkj6or:09515] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fe42288ff]
[runnervmkj6or:09515] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fe46a5ff5]
[runnervmkj6or:09515] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fe46bb0da]
[runnervmkj6or:09515] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fe46a5a55]
[runnervmkj6or:09515] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fe46a5a6f]
[runnervmkj6or:09515] [ 8] plumed_master(+0x146dd)[0x55c6352a86dd]
[runnervmkj6or:09515] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fe422a1ca]
[runnervmkj6or:09515] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fe422a28b]
[runnervmkj6or:09515] [11] plumed_master(+0x15365)[0x55c6352a9365]
[runnervmkj6or:09515] *** End of error message ***
</pre>
{% endraw %}
