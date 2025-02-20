**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az816-356:07861] *** Process received signal ***
[fv-az816-356:07861] Signal: Aborted (6)
[fv-az816-356:07861] Signal code:  (-6)
[fv-az816-356:07861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6f47645330]
[fv-az816-356:07861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6f4769eb2c]
[fv-az816-356:07861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6f4764527e]
[fv-az816-356:07861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6f476288ff]
[fv-az816-356:07861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6f47aa5ff5]
[fv-az816-356:07861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6f47abb0da]
[fv-az816-356:07861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6f47aa5a55]
[fv-az816-356:07861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6f47aa5a6f]
[fv-az816-356:07861] [ 8] plumed(+0x146dd)[0x556cc5f9c6dd]
[fv-az816-356:07861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6f4762a1ca]
[fv-az816-356:07861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6f4762a28b]
[fv-az816-356:07861] [11] plumed(+0x15365)[0x556cc5f9d365]
[fv-az816-356:07861] *** End of error message ***
</pre>
{% endraw %}
