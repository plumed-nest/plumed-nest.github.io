**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az816-356:07810] *** Process received signal ***
[fv-az816-356:07810] Signal: Aborted (6)
[fv-az816-356:07810] Signal code:  (-6)
[fv-az816-356:07810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4931a45330]
[fv-az816-356:07810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4931a9eb2c]
[fv-az816-356:07810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4931a4527e]
[fv-az816-356:07810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4931a288ff]
[fv-az816-356:07810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4931ea5ff5]
[fv-az816-356:07810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4931ebb0da]
[fv-az816-356:07810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4931ea5a55]
[fv-az816-356:07810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4931ea5a6f]
[fv-az816-356:07810] [ 8] plumed(+0x146dd)[0x5629324776dd]
[fv-az816-356:07810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4931a2a1ca]
[fv-az816-356:07810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4931a2a28b]
[fv-az816-356:07810] [11] plumed(+0x15365)[0x562932478365]
[fv-az816-356:07810] *** End of error message ***
</pre>
{% endraw %}
