# oidc-sub-probe

Throwaway. Determines empirically how GitHub composes the OIDC `sub` claim when
subject customization is enabled. Contains no secrets and touches no cloud
account: the workflows mint an OIDC token, decode the payload locally, and print
a fixed list of non-sensitive identity claims. The token itself is never printed.

Delete this repository once the claim formats are recorded.
# probe
