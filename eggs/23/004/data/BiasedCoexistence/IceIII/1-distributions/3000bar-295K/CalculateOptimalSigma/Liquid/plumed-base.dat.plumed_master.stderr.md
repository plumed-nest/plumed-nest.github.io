**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[fv-az1691-811:07860] *** Process received signal ***
[fv-az1691-811:07860] Signal: Aborted (6)
[fv-az1691-811:07860] Signal code:  (-6)
[fv-az1691-811:07860] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f598e845330]
[fv-az1691-811:07860] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f598e89eb2c]
[fv-az1691-811:07860] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f598e84527e]
[fv-az1691-811:07860] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f598e8288ff]
[fv-az1691-811:07860] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f598eca5ff5]
[fv-az1691-811:07860] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f598ecbb0da]
[fv-az1691-811:07860] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f598eca5a55]
[fv-az1691-811:07860] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f598eca5a6f]
[fv-az1691-811:07860] [ 8] plumed_master(+0x146dd)[0x5611b5e276dd]
[fv-az1691-811:07860] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f598e82a1ca]
[fv-az1691-811:07860] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f598e82a28b]
[fv-az1691-811:07860] [11] plumed_master(+0x15365)[0x5611b5e28365]
[fv-az1691-811:07860] *** End of error message ***
</pre>
{% endraw %}
