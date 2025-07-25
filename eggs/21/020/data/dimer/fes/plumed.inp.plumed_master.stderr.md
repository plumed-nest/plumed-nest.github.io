**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:10068] *** Process received signal ***
[pkrvmpptgkbjq6m:10068] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10068] Signal code:  (-6)
[pkrvmpptgkbjq6m:10068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c8de45330]
[pkrvmpptgkbjq6m:10068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c8de9eb2c]
[pkrvmpptgkbjq6m:10068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c8de4527e]
[pkrvmpptgkbjq6m:10068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c8de288ff]
[pkrvmpptgkbjq6m:10068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c8e2a5ff5]
[pkrvmpptgkbjq6m:10068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c8e2bb0da]
[pkrvmpptgkbjq6m:10068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c8e2a5a55]
[pkrvmpptgkbjq6m:10068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c8e2a5a6f]
[pkrvmpptgkbjq6m:10068] [ 8] plumed_master(+0x146dd)[0x557addc186dd]
[pkrvmpptgkbjq6m:10068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c8de2a1ca]
[pkrvmpptgkbjq6m:10068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c8de2a28b]
[pkrvmpptgkbjq6m:10068] [11] plumed_master(+0x15365)[0x557addc19365]
[pkrvmpptgkbjq6m:10068] *** End of error message ***
</pre>
{% endraw %}
