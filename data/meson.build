i18n.merge_file(
    input: 'io.elementary.switchboard.locale.policy.in',
    output: 'io.elementary.switchboard.locale.policy',
    po_dir: join_paths(meson.source_root(), 'po', 'extra'),
    install: true,
    install_dir: polkit_actiondir
)

i18n.merge_file(
    input: 'io.elementary.switchboard.locale.appdata.xml.in',
    output: '@BASENAME@',
    po_dir: join_paths(meson.source_root(), 'po', 'extra'),
    install: true,
    install_dir: join_paths(datadir, 'metainfo')
)

install_data(
    'io.elementary.switchboard.locale.gschema.xml',
    install_dir: join_paths(datadir, 'glib-2.0', 'schemas')
)

install_data(
    'languagelist',
    'packages_blacklist',
    install_dir: pkgdatadir
)
