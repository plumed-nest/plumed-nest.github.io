**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:63926] *** Process received signal ***
[pkrvmf6wy0o8zjz:63926] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:63926] Signal code:  (-6)
[pkrvmf6wy0o8zjz:63926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff61b045330]
[pkrvmf6wy0o8zjz:63926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff61b09eb2c]
[pkrvmf6wy0o8zjz:63926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff61b04527e]
[pkrvmf6wy0o8zjz:63926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff61b0288ff]
[pkrvmf6wy0o8zjz:63926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff61b4a5ff5]
[pkrvmf6wy0o8zjz:63926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff61b4bb0da]
[pkrvmf6wy0o8zjz:63926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff61b4a5a55]
[pkrvmf6wy0o8zjz:63926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff61b4a5a6f]
[pkrvmf6wy0o8zjz:63926] [ 8] plumed_master(+0x146dd)[0x55cb0ffb36dd]
[pkrvmf6wy0o8zjz:63926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff61b02a1ca]
[pkrvmf6wy0o8zjz:63926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff61b02a28b]
[pkrvmf6wy0o8zjz:63926] [11] plumed_master(+0x15365)[0x55cb0ffb4365]
[pkrvmf6wy0o8zjz:63926] *** End of error message ***
</pre>
{% endraw %}
