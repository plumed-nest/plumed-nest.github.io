**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS6ST/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[fv-az1911-722:08654] *** Process received signal ***
[fv-az1911-722:08654] Signal: Aborted (6)
[fv-az1911-722:08654] Signal code:  (-6)
[fv-az1911-722:08654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc562045330]
[fv-az1911-722:08654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc56209eb2c]
[fv-az1911-722:08654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc56204527e]
[fv-az1911-722:08654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc5620288ff]
[fv-az1911-722:08654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc5624a5ff5]
[fv-az1911-722:08654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc5624bb0da]
[fv-az1911-722:08654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc5624a5a55]
[fv-az1911-722:08654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc5624a5a6f]
[fv-az1911-722:08654] [ 8] plumed_master(+0x146dd)[0x5569eab1a6dd]
[fv-az1911-722:08654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc56202a1ca]
[fv-az1911-722:08654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc56202a28b]
[fv-az1911-722:08654] [11] plumed_master(+0x15365)[0x5569eab1b365]
[fv-az1911-722:08654] *** End of error message ***
</pre>
{% endraw %}
