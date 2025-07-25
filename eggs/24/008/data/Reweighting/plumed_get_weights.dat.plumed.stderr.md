**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmpptgkbjq6m:07895] *** Process received signal ***
[pkrvmpptgkbjq6m:07895] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07895] Signal code:  (-6)
[pkrvmpptgkbjq6m:07895] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff26ca45330]
[pkrvmpptgkbjq6m:07895] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff26ca9eb2c]
[pkrvmpptgkbjq6m:07895] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff26ca4527e]
[pkrvmpptgkbjq6m:07895] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff26ca288ff]
[pkrvmpptgkbjq6m:07895] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff26cea5ff5]
[pkrvmpptgkbjq6m:07895] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff26cebb0da]
[pkrvmpptgkbjq6m:07895] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff26cea5a55]
[pkrvmpptgkbjq6m:07895] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff26cea5a6f]
[pkrvmpptgkbjq6m:07895] [ 8] plumed(+0x146dd)[0x55819ddc06dd]
[pkrvmpptgkbjq6m:07895] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff26ca2a1ca]
[pkrvmpptgkbjq6m:07895] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff26ca2a28b]
[pkrvmpptgkbjq6m:07895] [11] plumed(+0x15365)[0x55819ddc1365]
[pkrvmpptgkbjq6m:07895] *** End of error message ***
</pre>
{% endraw %}
