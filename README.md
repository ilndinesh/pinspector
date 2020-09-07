# pinspector
Python live objects inspector

# where to get?
https://pypi.org/project/pinspector/ \
pip install pinspector

# how to use?
from pinspector.server import PinServer \
pin = PinServer(port=5678, targets={'object1':some_object}) \
pin.start() \
... \
pin.stop()
