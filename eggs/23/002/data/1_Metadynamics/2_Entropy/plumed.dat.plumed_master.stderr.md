**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az816-356:07724] *** Process received signal ***
[fv-az816-356:07724] Signal: Aborted (6)
[fv-az816-356:07724] Signal code:  (-6)
[fv-az816-356:07724] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc304045330]
[fv-az816-356:07724] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc30409eb2c]
[fv-az816-356:07724] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc30404527e]
[fv-az816-356:07724] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc3040288ff]
[fv-az816-356:07724] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3044a5ff5]
[fv-az816-356:07724] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3044bb0da]
[fv-az816-356:07724] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3044a5a55]
[fv-az816-356:07724] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3044a5a6f]
[fv-az816-356:07724] [ 8] plumed_master(+0x146dd)[0x55d8461aa6dd]
[fv-az816-356:07724] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc30402a1ca]
[fv-az816-356:07724] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc30402a28b]
[fv-az816-356:07724] [11] plumed_master(+0x15365)[0x55d8461ab365]
[fv-az816-356:07724] *** End of error message ***
</pre>
{% endraw %}
