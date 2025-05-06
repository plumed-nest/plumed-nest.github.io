**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1781-652:67940] *** Process received signal ***
[fv-az1781-652:67940] Signal: Aborted (6)
[fv-az1781-652:67940] Signal code:  (-6)
[fv-az1781-652:67940] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a61a45330]
[fv-az1781-652:67940] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a61a9eb2c]
[fv-az1781-652:67940] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a61a4527e]
[fv-az1781-652:67940] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a61a288ff]
[fv-az1781-652:67940] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a61ea5ff5]
[fv-az1781-652:67940] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a61ebb0da]
[fv-az1781-652:67940] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a61ea5a55]
[fv-az1781-652:67940] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a61ea5a6f]
[fv-az1781-652:67940] [ 8] plumed_master(+0x146dd)[0x555de62e36dd]
[fv-az1781-652:67940] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a61a2a1ca]
[fv-az1781-652:67940] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a61a2a28b]
[fv-az1781-652:67940] [11] plumed_master(+0x15365)[0x555de62e4365]
[fv-az1781-652:67940] *** End of error message ***
</pre>
{% endraw %}
