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
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:12655] *** Process received signal ***
[pkrvmpptgkbjq6m:12655] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12655] Signal code:  (-6)
[pkrvmpptgkbjq6m:12655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b96a45330]
[pkrvmpptgkbjq6m:12655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b96a9eb2c]
[pkrvmpptgkbjq6m:12655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b96a4527e]
[pkrvmpptgkbjq6m:12655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b96a288ff]
[pkrvmpptgkbjq6m:12655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b96ea5ff5]
[pkrvmpptgkbjq6m:12655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b96ebb0da]
[pkrvmpptgkbjq6m:12655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b96ea5a55]
[pkrvmpptgkbjq6m:12655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b96ea5a6f]
[pkrvmpptgkbjq6m:12655] [ 8] plumed_master(+0x146dd)[0x55bcaf7346dd]
[pkrvmpptgkbjq6m:12655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b96a2a1ca]
[pkrvmpptgkbjq6m:12655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b96a2a28b]
[pkrvmpptgkbjq6m:12655] [11] plumed_master(+0x15365)[0x55bcaf735365]
[pkrvmpptgkbjq6m:12655] *** End of error message ***
</pre>
{% endraw %}
