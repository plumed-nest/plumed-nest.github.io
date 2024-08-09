**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: SPHERICAL_EXPANSION LABEL=SPEX_A SPECIES1=1-216 SPECIES2=217-432 SPECIES3=433-1080 HYPERPARAMS=     "max_radial": 6,     "max_angular": 1,     "compute_gradients": false,     "cutoff_function": {"type": "ShiftedCosine", "cutoff": {"value": 3.0, "unit": "AA"}, "smooth_width": {"value": 0.5, "unit": "AA"}},     "gaussian_density": {"type": "Constant", "gaussian_sigma": {"value": 0.5, "unit": "AA"}},     "radial_contribution": {"type": "GTO"}
Maybe a missing space or a typo?
[fv-az1019-654:04120] *** Process received signal ***
[fv-az1019-654:04120] Signal: Aborted (6)
[fv-az1019-654:04120] Signal code:  (-6)
[fv-az1019-654:04120] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5b06042520]
[fv-az1019-654:04120] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5b060969fc]
[fv-az1019-654:04120] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5b06042476]
[fv-az1019-654:04120] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5b060287f3]
[fv-az1019-654:04120] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5b064a2b9e]
[fv-az1019-654:04120] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5b064ae20c]
[fv-az1019-654:04120] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5b064ae277]
[fv-az1019-654:04120] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5b064ae52b]
[fv-az1019-654:04120] [ 8] plumed(+0x12f48)[0x5603f8ea8f48]
[fv-az1019-654:04120] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5b06029d90]
[fv-az1019-654:04120] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5b06029e40]
[fv-az1019-654:04120] [11] plumed(+0x131e5)[0x5603f8ea91e5]
[fv-az1019-654:04120] *** End of error message ***
</pre>
{% endraw %}
