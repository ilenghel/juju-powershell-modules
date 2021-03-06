###version 1.00
  - 21.08.2015
  - Added ``Carbon::Generate-StrongPassword``
  - Added ``Juju::Is-Leader``
  - Added ``Juju::Get-LeaderData``
  - Added ``Juju::Set-LeaderData``
  - Added ``Juju::Get-JujuRemoteUnitRelation`
  - Added ``Windows::Check-Membership``
  - Added ``Windows::Convert-SIDToFriendlyName``
  - Refactored ``Juju::Is-JujuMasterUnit``
  - Refactored ``Juju::Set-JujuRelation``
  - Refactored ``Juju::Get-JujuRelationParams``
  - Refactored ``Windows::Unmarshall-Object``
  - Refactored ``Windows::Marshall-Object``
  - Refactored ``Windows::Get-JujuUnitName``
  - Refactored ``Windows::Create-LocalAdmin``

###version 0.13
  - 10.05.2015
  - Added ``Windows::Remove-CharmState``

###version 0.12
  - 20.04.2015
  - Added ``Windows::Get-WindowsUser``
  - Refactored ``Windows::Create-LocalAdmin``
  - Refactored ``Windows::Add-WindowsUser``
  - Refactored ``Windows::Delete-WindowsUser``

###version 0.11
  - 06.04.2015
  - Improved ``Juju::Is-JujuMasterUnit`` logic.
    - If ``$PeerRelationName`` parameter is given, the first peer is considered the master unit.

###version 0.10
  - 30.03.2015
  - First commit.