**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:09058] *** Process received signal ***
[pkrvmpptgkbjq6m:09058] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09058] Signal code:  (-6)
[pkrvmpptgkbjq6m:09058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0945645330]
[pkrvmpptgkbjq6m:09058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f094569eb2c]
[pkrvmpptgkbjq6m:09058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f094564527e]
[pkrvmpptgkbjq6m:09058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f09456288ff]
[pkrvmpptgkbjq6m:09058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0945aa5ff5]
[pkrvmpptgkbjq6m:09058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0945abb0da]
[pkrvmpptgkbjq6m:09058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0945aa5a55]
[pkrvmpptgkbjq6m:09058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0945aa5a6f]
[pkrvmpptgkbjq6m:09058] [ 8] plumed_master(+0x146dd)[0x563d906666dd]
[pkrvmpptgkbjq6m:09058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f094562a1ca]
[pkrvmpptgkbjq6m:09058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f094562a28b]
[pkrvmpptgkbjq6m:09058] [11] plumed_master(+0x15365)[0x563d90667365]
[pkrvmpptgkbjq6m:09058] *** End of error message ***
</pre>
{% endraw %}
