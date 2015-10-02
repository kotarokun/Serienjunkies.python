# Create Serienjunkies-RSS for Flexget

Use these file with Flexget on Windows:

    tasks:
      create_rss:
        exec:
          auto_escape: yes
          allow_background: yes
          on_start:
            phase: "c:/Users/Administrator/Flexget/serienjunkies_rss.py"
        priority: 0
        no_entries_ok: yes
        manual: yes
