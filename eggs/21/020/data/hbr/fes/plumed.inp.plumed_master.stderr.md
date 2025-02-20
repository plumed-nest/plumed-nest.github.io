**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az816-356:11757] *** Process received signal ***
[fv-az816-356:11757] Signal: Aborted (6)
[fv-az816-356:11757] Signal code:  (-6)
[fv-az816-356:11757] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f624f245330]
[fv-az816-356:11757] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f624f29eb2c]
[fv-az816-356:11757] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f624f24527e]
[fv-az816-356:11757] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f624f2288ff]
[fv-az816-356:11757] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f624f6a5ff5]
[fv-az816-356:11757] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f624f6bb0da]
[fv-az816-356:11757] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f624f6a5a55]
[fv-az816-356:11757] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f624f6a5a6f]
[fv-az816-356:11757] [ 8] plumed_master(+0x146dd)[0x5640c4c9c6dd]
[fv-az816-356:11757] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f624f22a1ca]
[fv-az816-356:11757] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f624f22a28b]
[fv-az816-356:11757] [11] plumed_master(+0x15365)[0x5640c4c9d365]
[fv-az816-356:11757] *** End of error message ***
</pre>
{% endraw %}
