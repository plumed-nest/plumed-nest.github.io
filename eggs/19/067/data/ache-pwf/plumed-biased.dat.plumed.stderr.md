**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1950-95:66311] *** Process received signal ***
[fv-az1950-95:66311] Signal: Aborted (6)
[fv-az1950-95:66311] Signal code:  (-6)
[fv-az1950-95:66311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f12f8245330]
[fv-az1950-95:66311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f12f829eb2c]
[fv-az1950-95:66311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f12f824527e]
[fv-az1950-95:66311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f12f82288ff]
[fv-az1950-95:66311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f12f86a5ff5]
[fv-az1950-95:66311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f12f86bb0da]
[fv-az1950-95:66311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f12f86a5a55]
[fv-az1950-95:66311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f12f86a5a6f]
[fv-az1950-95:66311] [ 8] plumed(+0x146dd)[0x558fe37266dd]
[fv-az1950-95:66311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f12f822a1ca]
[fv-az1950-95:66311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f12f822a28b]
[fv-az1950-95:66311] [11] plumed(+0x15365)[0x558fe3727365]
[fv-az1950-95:66311] *** End of error message ***
</pre>
{% endraw %}
