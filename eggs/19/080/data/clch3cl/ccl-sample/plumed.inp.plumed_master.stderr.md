**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ccl-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[fv-az1979-234:67129] *** Process received signal ***
[fv-az1979-234:67129] Signal: Aborted (6)
[fv-az1979-234:67129] Signal code:  (-6)
[fv-az1979-234:67129] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f913b845330]
[fv-az1979-234:67129] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f913b89eb2c]
[fv-az1979-234:67129] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f913b84527e]
[fv-az1979-234:67129] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f913b8288ff]
[fv-az1979-234:67129] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f913bca5ff5]
[fv-az1979-234:67129] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f913bcbb0da]
[fv-az1979-234:67129] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f913bca5a55]
[fv-az1979-234:67129] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f913bca5a6f]
[fv-az1979-234:67129] [ 8] plumed_master(+0x146dd)[0x55962abfd6dd]
[fv-az1979-234:67129] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f913b82a1ca]
[fv-az1979-234:67129] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f913b82a28b]
[fv-az1979-234:67129] [11] plumed_master(+0x15365)[0x55962abfe365]
[fv-az1979-234:67129] *** End of error message ***
</pre>
{% endraw %}
