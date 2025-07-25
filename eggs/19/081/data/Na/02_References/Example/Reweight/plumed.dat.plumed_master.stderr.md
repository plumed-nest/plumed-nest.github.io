**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:13635] *** Process received signal ***
[pkrvmpptgkbjq6m:13635] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13635] Signal code:  (-6)
[pkrvmpptgkbjq6m:13635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8655445330]
[pkrvmpptgkbjq6m:13635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f865549eb2c]
[pkrvmpptgkbjq6m:13635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f865544527e]
[pkrvmpptgkbjq6m:13635] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f86554288ff]
[pkrvmpptgkbjq6m:13635] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f86558a5ff5]
[pkrvmpptgkbjq6m:13635] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f86558bb0da]
[pkrvmpptgkbjq6m:13635] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f86558a5a55]
[pkrvmpptgkbjq6m:13635] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f86558a5a6f]
[pkrvmpptgkbjq6m:13635] [ 8] plumed_master(+0x146dd)[0x55777a8266dd]
[pkrvmpptgkbjq6m:13635] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f865542a1ca]
[pkrvmpptgkbjq6m:13635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f865542a28b]
[pkrvmpptgkbjq6m:13635] [11] plumed_master(+0x15365)[0x55777a827365]
[pkrvmpptgkbjq6m:13635] *** End of error message ***
</pre>
{% endraw %}
