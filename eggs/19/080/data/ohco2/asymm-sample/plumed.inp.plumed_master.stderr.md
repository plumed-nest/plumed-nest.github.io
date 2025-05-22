**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:39958] *** Process received signal ***
[pkrvmf6wy0o8zjz:39958] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:39958] Signal code:  (-6)
[pkrvmf6wy0o8zjz:39958] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6d1845330]
[pkrvmf6wy0o8zjz:39958] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6d189eb2c]
[pkrvmf6wy0o8zjz:39958] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6d184527e]
[pkrvmf6wy0o8zjz:39958] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6d18288ff]
[pkrvmf6wy0o8zjz:39958] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6d1ca5ff5]
[pkrvmf6wy0o8zjz:39958] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6d1cbb0da]
[pkrvmf6wy0o8zjz:39958] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6d1ca5a55]
[pkrvmf6wy0o8zjz:39958] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6d1ca5a6f]
[pkrvmf6wy0o8zjz:39958] [ 8] plumed_master(+0x146dd)[0x564ea5d306dd]
[pkrvmf6wy0o8zjz:39958] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6d182a1ca]
[pkrvmf6wy0o8zjz:39958] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6d182a28b]
[pkrvmf6wy0o8zjz:39958] [11] plumed_master(+0x15365)[0x564ea5d31365]
[pkrvmf6wy0o8zjz:39958] *** End of error message ***
</pre>
{% endraw %}
