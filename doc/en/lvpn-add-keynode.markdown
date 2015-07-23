% LVPN-ADD-KEYNODE(1) Manual de LibreVPN | lvpn
% Nicolás Reynolds <fauno@endefensadelsl.org>
% 2015

# NAME

Adds keynode URLs to a given node


# SYNOPSIS

_lvpn add-keynode_ [-h] [-l] [-u] local-node keynode:hosts.git [keynode2:hosts.git]


# OPTIONS

-h
:    This message

-l
:    List keynodes of this node

-u
:    Update keynodes bringing changes and uploading ours


# DESCRIPTION

Configures local-node to obtain node files from the given URLs.

Converts the local-node hosts dir into a git repository that will push
and pull changes to the given repositories.


# SEE ALSO

_git(1)_ _lvpn-create-keynode(1)_
