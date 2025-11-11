**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervmw9dnm:13127] *** Process received signal ***
[runnervmw9dnm:13127] Signal: Aborted (6)
[runnervmw9dnm:13127] Signal code:  (-6)
[runnervmw9dnm:13127] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f182f645330]
[runnervmw9dnm:13127] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f182f69eb2c]
[runnervmw9dnm:13127] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f182f64527e]
[runnervmw9dnm:13127] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f182f6288ff]
[runnervmw9dnm:13127] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f182faa5ff5]
[runnervmw9dnm:13127] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f182fabb0da]
[runnervmw9dnm:13127] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f182faa5a55]
[runnervmw9dnm:13127] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f182faa5a6f]
[runnervmw9dnm:13127] [ 8] plumed(+0x146dd)[0x556e211b16dd]
[runnervmw9dnm:13127] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f182f62a1ca]
[runnervmw9dnm:13127] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f182f62a28b]
[runnervmw9dnm:13127] [11] plumed(+0x15365)[0x556e211b2365]
[runnervmw9dnm:13127] *** End of error message ***
</pre>
{% endraw %}
