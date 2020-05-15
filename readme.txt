Round 1 for the U3M 1.1 specification.

This folder contains:
    - readme.txt:
        this file
    - changes.txt:
        a list of all changes between U3M 1.0 and U3M 1.1
    - u3m.pdf:
        non-technical documentation
    - CODEOWNERS:
        a file for github
    - LICENSE:
        license under which everything herein is put
    - README.md:
        readme for github
    - spec/
        the specification files for the technical details
        - u3m_schema.json
            json schema for *.u3m files
        - u3m_additional_spec.txt:
            general additional notes to u3m files (*.u3m and *.u3ma)
        - u3m_additional_spec_u3ma.txt:
            documentation for *.u3ma files (has no accompaning schema file)
        - u3m_additional_spec_u3m.txt:
            additional notes to u3m_schema.json
        - u3m_open_questions.txt:
            a list of all open, resolved and postponed questions regarding U3M 1.1
    - utils/
        contains additional utilities, mainly to help developers - those files are not part of the specification!
        - u3machecker.exe:
            test program to check your generated *.u3ma files or generate *.u3ma files
            if there is any conflict between the results of this tool and the u3ma specification, please drop us a note on https://github.com/vizoogmbh/u3m,
            so we can fix the bug. In such case, please stick to the u3ma specification
            uses zlib https://zlib.net/ for compression/decompression

If you have any questions or suggestions feel free to reach out via https://github.com/vizoogmbh/u3m or email to info@vizoo3d.com