# Content and maintenance guidelines

The intended audience is AIRF 4201 students who **use** computational tools but are **not expected to code**.

For each new notebook:
- Explain the decision/problem being illustrated and intended learning outcomes.
- Include clear instructions and an editable input area; avoid making students modify Python code.
- Check that the notebook runs in a fresh Colab runtime, without private Drive files or local filesystem paths.
- Prefer bundled, approved, or synthetic datasets and clearly identify assumptions and sources.
- Ensure outputs are interpretable as an aviation management decision, not merely calculations.
- Place student-facing demonstrations under `examples/`, guided activities under `activities/`, and their approved data under `data/`.
- Put reusable material in `shared/` only when it is actually used by several modules.
- Keep solutions, student work, grade data, restricted content, and unreleased assessments elsewhere.

**Versioning:** Preserve tested teaching states with Git tags (e.g. `fall-2026`) when appropriate. Use meaningful names such as `M09_nested_booking_limits_dashboard.ipynb`. D2L remains the official course and submission platform.

**Copyright/licensing:** Check permissions for sources and datasets. Do not apply an open-source license until the course owner approves appropriate terms.
