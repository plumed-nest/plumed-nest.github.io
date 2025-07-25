**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:08888] *** Process received signal ***
[pkrvmpptgkbjq6m:08888] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08888] Signal code:  (-6)
[pkrvmpptgkbjq6m:08888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabef845330]
[pkrvmpptgkbjq6m:08888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabef89eb2c]
[pkrvmpptgkbjq6m:08888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabef84527e]
[pkrvmpptgkbjq6m:08888] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabef8288ff]
[pkrvmpptgkbjq6m:08888] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabefca5ff5]
[pkrvmpptgkbjq6m:08888] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabefcbb0da]
[pkrvmpptgkbjq6m:08888] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabefca5a55]
[pkrvmpptgkbjq6m:08888] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabefca5a6f]
[pkrvmpptgkbjq6m:08888] [ 8] plumed(+0x146dd)[0x55ca310596dd]
[pkrvmpptgkbjq6m:08888] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabef82a1ca]
[pkrvmpptgkbjq6m:08888] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabef82a28b]
[pkrvmpptgkbjq6m:08888] [11] plumed(+0x15365)[0x55ca3105a365]
[pkrvmpptgkbjq6m:08888] *** End of error message ***
</pre>
{% endraw %}
