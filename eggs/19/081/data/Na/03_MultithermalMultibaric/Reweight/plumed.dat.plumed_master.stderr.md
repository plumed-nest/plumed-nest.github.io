**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmvrwv9:10921] *** Process received signal ***
[runnervmvrwv9:10921] Signal: Aborted (6)
[runnervmvrwv9:10921] Signal code:  (-6)
[runnervmvrwv9:10921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd5a645330]
[runnervmvrwv9:10921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd5a69eb2c]
[runnervmvrwv9:10921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd5a64527e]
[runnervmvrwv9:10921] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd5a6288ff]
[runnervmvrwv9:10921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd5aaa5ff5]
[runnervmvrwv9:10921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd5aabb0da]
[runnervmvrwv9:10921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd5aaa5a55]
[runnervmvrwv9:10921] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd5aaa5a6f]
[runnervmvrwv9:10921] [ 8] plumed_master(+0x146dd)[0x561ef2e746dd]
[runnervmvrwv9:10921] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd5a62a1ca]
[runnervmvrwv9:10921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd5a62a28b]
[runnervmvrwv9:10921] [11] plumed_master(+0x15365)[0x561ef2e75365]
[runnervmvrwv9:10921] *** End of error message ***
</pre>
{% endraw %}
