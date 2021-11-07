
# CSS Cascade

CSS works based on a `cascade` when applying rules.

In case of conflicting rules we follow the following decision tree:


                    Conflict in rule
                    declaration
                       |
                       V
                    Different origin   -- YES -> Use declaration with higher priority origin
                    or importance?
                       |
                       V
                    Is one rule
                    an HTML            -- YES -> Use in declaration
                    **inline-style**?
                       |
                       V
                    Do CSS selectors
                    have different    -- YES -> Use declartion with highest specifity
                    **specifity**?
                       |
                       V
                    Use declaration that
                    comes later in **source order**