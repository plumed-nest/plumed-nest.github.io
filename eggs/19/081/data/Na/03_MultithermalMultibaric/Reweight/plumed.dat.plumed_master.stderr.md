**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:13844] *** Process received signal ***
[pkrvmpptgkbjq6m:13844] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13844] Signal code:  (-6)
[pkrvmpptgkbjq6m:13844] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64d7845330]
[pkrvmpptgkbjq6m:13844] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64d789eb2c]
[pkrvmpptgkbjq6m:13844] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64d784527e]
[pkrvmpptgkbjq6m:13844] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64d78288ff]
[pkrvmpptgkbjq6m:13844] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64d7ca5ff5]
[pkrvmpptgkbjq6m:13844] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64d7cbb0da]
[pkrvmpptgkbjq6m:13844] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64d7ca5a55]
[pkrvmpptgkbjq6m:13844] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64d7ca5a6f]
[pkrvmpptgkbjq6m:13844] [ 8] plumed_master(+0x146dd)[0x5564880af6dd]
[pkrvmpptgkbjq6m:13844] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64d782a1ca]
[pkrvmpptgkbjq6m:13844] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64d782a28b]
[pkrvmpptgkbjq6m:13844] [11] plumed_master(+0x15365)[0x5564880b0365]
[pkrvmpptgkbjq6m:13844] *** End of error message ***
</pre>
{% endraw %}
