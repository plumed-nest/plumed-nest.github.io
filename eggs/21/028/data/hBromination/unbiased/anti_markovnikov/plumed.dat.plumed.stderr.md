**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10803] *** Process received signal ***
[runnervmw9dnm:10803] Signal: Aborted (6)
[runnervmw9dnm:10803] Signal code:  (-6)
[runnervmw9dnm:10803] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef4ec45330]
[runnervmw9dnm:10803] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef4ec9eb2c]
[runnervmw9dnm:10803] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef4ec4527e]
[runnervmw9dnm:10803] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef4ec288ff]
[runnervmw9dnm:10803] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef4f0a5ff5]
[runnervmw9dnm:10803] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef4f0bb0da]
[runnervmw9dnm:10803] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef4f0a5a55]
[runnervmw9dnm:10803] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef4f0a5a6f]
[runnervmw9dnm:10803] [ 8] plumed(+0x146dd)[0x564170a1c6dd]
[runnervmw9dnm:10803] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef4ec2a1ca]
[runnervmw9dnm:10803] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef4ec2a28b]
[runnervmw9dnm:10803] [11] plumed(+0x15365)[0x564170a1d365]
[runnervmw9dnm:10803] *** End of error message ***
</pre>
{% endraw %}
