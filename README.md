# odoo-view-pocalypse-convert
Patch (dirty/wip) to migrate repository xml files for Odoo modifiers/domain to python expression.

The patch must be applied in the version corresponding to https://github.com/odoo/odoo/pull/104741 (juste after the pr commits)
You must keep the states attributes on the fields before modifying the files.
Install all addons whose files need to be updated.

NB: This patch will not be cleaned up, or even maintained.
