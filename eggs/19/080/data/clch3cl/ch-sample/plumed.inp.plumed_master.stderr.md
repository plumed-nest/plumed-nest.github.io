**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:11616] *** Process received signal ***
[pkrvmpptgkbjq6m:11616] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11616] Signal code:  (-6)
[pkrvmpptgkbjq6m:11616] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9504a45330]
[pkrvmpptgkbjq6m:11616] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9504a9eb2c]
[pkrvmpptgkbjq6m:11616] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9504a4527e]
[pkrvmpptgkbjq6m:11616] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9504a288ff]
[pkrvmpptgkbjq6m:11616] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9504ea5ff5]
[pkrvmpptgkbjq6m:11616] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9504ebb0da]
[pkrvmpptgkbjq6m:11616] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9504ea5a55]
[pkrvmpptgkbjq6m:11616] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9504ea5a6f]
[pkrvmpptgkbjq6m:11616] [ 8] plumed_master(+0x146dd)[0x5577c230e6dd]
[pkrvmpptgkbjq6m:11616] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9504a2a1ca]
[pkrvmpptgkbjq6m:11616] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9504a2a28b]
[pkrvmpptgkbjq6m:11616] [11] plumed_master(+0x15365)[0x5577c230f365]
[pkrvmpptgkbjq6m:11616] *** End of error message ***
</pre>
{% endraw %}
