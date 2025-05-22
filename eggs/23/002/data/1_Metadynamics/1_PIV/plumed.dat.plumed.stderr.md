**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmf6wy0o8zjz:37027] *** Process received signal ***
[pkrvmf6wy0o8zjz:37027] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37027] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37027] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4925845330]
[pkrvmf6wy0o8zjz:37027] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f492589eb2c]
[pkrvmf6wy0o8zjz:37027] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f492584527e]
[pkrvmf6wy0o8zjz:37027] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f49258288ff]
[pkrvmf6wy0o8zjz:37027] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4925ca5ff5]
[pkrvmf6wy0o8zjz:37027] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4925cbb0da]
[pkrvmf6wy0o8zjz:37027] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4925ca5a55]
[pkrvmf6wy0o8zjz:37027] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4925ca5a6f]
[pkrvmf6wy0o8zjz:37027] [ 8] plumed(+0x146dd)[0x5558a97446dd]
[pkrvmf6wy0o8zjz:37027] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f492582a1ca]
[pkrvmf6wy0o8zjz:37027] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f492582a28b]
[pkrvmf6wy0o8zjz:37027] [11] plumed(+0x15365)[0x5558a9745365]
[pkrvmf6wy0o8zjz:37027] *** End of error message ***
</pre>
{% endraw %}
