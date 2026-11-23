## Day 07 — Bootstrap Components, Forms & Interaction

**1. What did I build today?**

A page with an offcanvas navbar, a modal contact form with validation styles, and an FAQ accordion, all using Bootstrap components only.

**2. What bug/difficulty did I solve?**

The Contact link needed to open the modal and close the offcanvas at the same time, so I used a button with both `data-bs-toggle="modal"` and `data-bs-dismiss="offcanvas"`. I also removed unnecessary custom JavaScript because Bootstrap's data attributes handle the interaction.

**3. What concept can I explain clearly?**

Bootstrap data attributes: `data-bs-toggle` opens a component, `data-bs-target` selects which one, and `data-bs-dismiss` closes it. The accordion uses `data-bs-parent` so only one item is open at a time.

**4. What remains incomplete?**

The form does not send data anywhere, because it needs a backend. 