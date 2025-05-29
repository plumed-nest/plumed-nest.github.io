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
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:68658] *** Process received signal ***
[pkrvmf6wy0o8zjz:68658] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68658] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68658] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f043ba45330]
[pkrvmf6wy0o8zjz:68658] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f043ba9eb2c]
[pkrvmf6wy0o8zjz:68658] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f043ba4527e]
[pkrvmf6wy0o8zjz:68658] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f043ba288ff]
[pkrvmf6wy0o8zjz:68658] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f043bea5ff5]
[pkrvmf6wy0o8zjz:68658] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f043bebb0da]
[pkrvmf6wy0o8zjz:68658] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f043bea5a55]
[pkrvmf6wy0o8zjz:68658] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f043bea5a6f]
[pkrvmf6wy0o8zjz:68658] [ 8] plumed_master(+0x146dd)[0x55eb9a9646dd]
[pkrvmf6wy0o8zjz:68658] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f043ba2a1ca]
[pkrvmf6wy0o8zjz:68658] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f043ba2a28b]
[pkrvmf6wy0o8zjz:68658] [11] plumed_master(+0x15365)[0x55eb9a965365]
[pkrvmf6wy0o8zjz:68658] *** End of error message ***
</pre>
{% endraw %}
