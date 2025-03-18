**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1950-95:66389] *** Process received signal ***
[fv-az1950-95:66389] Signal: Aborted (6)
[fv-az1950-95:66389] Signal code:  (-6)
[fv-az1950-95:66389] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4942645330]
[fv-az1950-95:66389] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f494269eb2c]
[fv-az1950-95:66389] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f494264527e]
[fv-az1950-95:66389] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f49426288ff]
[fv-az1950-95:66389] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4942aa5ff5]
[fv-az1950-95:66389] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4942abb0da]
[fv-az1950-95:66389] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4942aa5a55]
[fv-az1950-95:66389] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4942aa5a6f]
[fv-az1950-95:66389] [ 8] plumed(+0x146dd)[0x56231a7866dd]
[fv-az1950-95:66389] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f494262a1ca]
[fv-az1950-95:66389] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f494262a28b]
[fv-az1950-95:66389] [11] plumed(+0x15365)[0x56231a787365]
[fv-az1950-95:66389] *** End of error message ***
</pre>
{% endraw %}
