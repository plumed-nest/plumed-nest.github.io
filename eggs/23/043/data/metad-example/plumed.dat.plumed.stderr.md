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
[fv-az1433-905:67675] *** Process received signal ***
[fv-az1433-905:67675] Signal: Aborted (6)
[fv-az1433-905:67675] Signal code:  (-6)
[fv-az1433-905:67675] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fefab042520]
[fv-az1433-905:67675] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fefab0969fc]
[fv-az1433-905:67675] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fefab042476]
[fv-az1433-905:67675] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fefab0287f3]
[fv-az1433-905:67675] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fefab4a4f26]
[fv-az1433-905:67675] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fefab4b6d9c]
[fv-az1433-905:67675] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fefab4b6e07]
[fv-az1433-905:67675] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fefab4b70bb]
[fv-az1433-905:67675] [ 8] plumed(+0x12f48)[0x5609db1b4f48]
[fv-az1433-905:67675] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fefab029d90]
[fv-az1433-905:67675] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fefab029e40]
[fv-az1433-905:67675] [11] plumed(+0x131e5)[0x5609db1b51e5]
[fv-az1433-905:67675] *** End of error message ***
</pre>
{% endraw %}
