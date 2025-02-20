**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1911-722:09602] *** Process received signal ***
[fv-az1911-722:09602] Signal: Aborted (6)
[fv-az1911-722:09602] Signal code:  (-6)
[fv-az1911-722:09602] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3a57045330]
[fv-az1911-722:09602] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3a5709eb2c]
[fv-az1911-722:09602] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3a5704527e]
[fv-az1911-722:09602] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3a570288ff]
[fv-az1911-722:09602] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3a574a5ff5]
[fv-az1911-722:09602] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3a574bb0da]
[fv-az1911-722:09602] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3a574a5a55]
[fv-az1911-722:09602] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3a574a5a6f]
[fv-az1911-722:09602] [ 8] plumed_master(+0x146dd)[0x5566eb6bd6dd]
[fv-az1911-722:09602] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3a5702a1ca]
[fv-az1911-722:09602] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3a5702a28b]
[fv-az1911-722:09602] [11] plumed_master(+0x15365)[0x5566eb6be365]
[fv-az1911-722:09602] *** End of error message ***
</pre>
{% endraw %}
