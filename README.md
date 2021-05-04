# CLASS_SInu
CLASS code for computing the CMB anisotropy power spectra and the matter power spectrum with massless self-interacting neutrinos. The associated paper can be found here https://arxiv.org/abs/2011.12315.

**Requirements:**

Same as CLASS version 2.9.0

**Key Changes:**

The _idr_ species in CLASS is being used as the interacting neutrinos. The example input file sinu_example.ini explains the new input parameters.

_N_idr_ : Number of neutrino species

_xi_idr_ : Temperature of neutrino relative to photon

_log_G_eff_idr_i_ : The 4-Fermi coupling strength for the i-th neutrino species

N.B.- Alongwith _N_idr_, one can use the usual _N_ur_ parameter for relativistic species. However, the _N_ur_ part will not have self-interaction.

**Warning**
1. The _idm_ species has been deactivated in the code. Therefore, always set _Omega_idm_dr_ = 0.
2. The default _N_ur_ has been set to 0.

**Authors**

Anirban Das & Subhajit Ghosh

**Citation**

If you use the code in your work, please cite this repository, the associated paper https://arxiv.org/abs/2011.12315, and the original CLASS paper https://arxiv.org/abs/1104.2933.
