**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[fv-az1979-234:67197] *** Process received signal ***
[fv-az1979-234:67197] Signal: Aborted (6)
[fv-az1979-234:67197] Signal code:  (-6)
[fv-az1979-234:67197] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c47845330]
[fv-az1979-234:67197] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c4789eb2c]
[fv-az1979-234:67197] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c4784527e]
[fv-az1979-234:67197] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c478288ff]
[fv-az1979-234:67197] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c47ca5ff5]
[fv-az1979-234:67197] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c47cbb0da]
[fv-az1979-234:67197] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c47ca5a55]
[fv-az1979-234:67197] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c47ca5a6f]
[fv-az1979-234:67197] [ 8] plumed_master(+0x146dd)[0x563eb157b6dd]
[fv-az1979-234:67197] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c4782a1ca]
[fv-az1979-234:67197] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c4782a28b]
[fv-az1979-234:67197] [11] plumed_master(+0x15365)[0x563eb157c365]
[fv-az1979-234:67197] *** End of error message ***
</pre>
{% endraw %}
