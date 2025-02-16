**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az1979-234:65383] *** Process received signal ***
[fv-az1979-234:65383] Signal: Aborted (6)
[fv-az1979-234:65383] Signal code:  (-6)
[fv-az1979-234:65383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa341445330]
[fv-az1979-234:65383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa34149eb2c]
[fv-az1979-234:65383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa34144527e]
[fv-az1979-234:65383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3414288ff]
[fv-az1979-234:65383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3418a5ff5]
[fv-az1979-234:65383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3418bb0da]
[fv-az1979-234:65383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3418a5a55]
[fv-az1979-234:65383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3418a5a6f]
[fv-az1979-234:65383] [ 8] plumed(+0x146dd)[0x5569afe1b6dd]
[fv-az1979-234:65383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa34142a1ca]
[fv-az1979-234:65383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa34142a28b]
[fv-az1979-234:65383] [11] plumed(+0x15365)[0x5569afe1c365]
[fv-az1979-234:65383] *** End of error message ***
</pre>
{% endraw %}
