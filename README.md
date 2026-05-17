## Overview
Debugged a production routing failure in a legacy PHP healthcare system impacting critical hospital workflows.

## Root Cause
- Conflicting routing behavior between Apache `mod_rewrite` and PHP entry points
- Undocumented module-level dependencies affecting request resolution

## Investigation
- Traced full HTTP request lifecycle across Apache → PHP routing layers
- Reconstructed routing flow from fragmented entry points and server rules
- Identified missing rewrite conditions causing route misdirection

## Fix
- Aligned Apache rewrite rules with application-level routing logic
- Standardized entry point resolution across modules
- Preserved backward compatibility for existing production workflows

## Impact
- Restored critical production routing paths
- Eliminated routing inconsistencies across workflows
- Reduced risk of future routing misconfiguration in legacy system
