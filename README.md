# class_SInu
CLASS code for computing the CMB anisotropy power spectra and the matter power spectrum with massless self-interacting neutrinos.

**Requirements:**

Same as CLASS version 2.9.0

**Key Changes:**

The _idr_ species in CLASS is being used as the interacting neutrinos. The example input file sinu_example.ini explains the new input parameters.
N_idr -- Number of neutrino species
xi_idr -- Temperature of neutrino relative to photon
log_G_eff_idr_i -- The 4-Fermi coupling strength for the i-th neutrino species

N.B.- Alongwith N_idr, one can use the usual N_ur parameter for relativistic species. However, the N_ur part will not have self-interaction.

**Warning**
1. The _idm_ species has been deactivated in the code. Therefore, always set Omega_idm_dr = 0.
2. The default N_ur has been set to 0.

**Citation**

If you use the code, please cite this repository and the associated paper https://arxiv.org/abs/2011.12315.
